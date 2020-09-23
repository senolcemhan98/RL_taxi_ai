# RL_taxi_ai

# Taxi AI

![image](https://user-images.githubusercontent.com/58151691/94065058-44b7d500-fdf3-11ea-8584-f722a94c4ea2.png)

Bu çalışmada Open AI - Gym enviroment'ı olan "Taxiv-3" ile Reinforcemen Q - Learning alıştırması yapılmıştır.

Amaç : Taxi ile yolcuyu alıp arış noktasına iletmek.

## Action'lar : 
  - Sağ
  - Sol
  - Yukarı
  - Aşağı
  - Yolcu Al
  - Yolcu Bırak
  
# Enviroment renkleri ne anlama gelir?

- mavi : Yolcunun bulunduğu yer
- mor  : Yolcunun ineceği nokta
- sarı : Taksinin konumu. (Taksini içerisi boş)
- yeşil: Taksinin konumu. (Yolcu taksinin içerisinde)

# Ödüllendirme Sistemi (Reward):
- Her yaptığın action için -1,
- Yanlış yerde yolcu alma - bırakma eylemleri -10
- Yolcu teslimi +20
