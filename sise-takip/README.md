# Şişe Takip 🍾

Barda şişe açtıran müşterilerin **şişede kalan miktarını** takip eden tek sayfalık web uygulaması.

- Menüdeki şişe alkoller (Whisky Scotch / Irish / Bourbon / Malt, Konyak, Cin, Rom, Vermut, Tekila, Votka, Likör) için **pixel-art şişe** çizimleri
- Her **Tek** / **Duble** / özel ml servisinde şişedeki sıvı seviyesi animasyonla düşer
- Kalan ml ve **"kaç duble / kaç tek daha içilebilir"** hesabı, duble göstergesi (her kare = 1 duble)
- Azalan şişe uyarısı, biten şişeler, servis geçmişi, geri alma
- Tek / duble ölçüleri ayarlardan değiştirilebilir (varsayılan 40 ml / 80 ml)
- Yayınlanan sürümde kayıtlar **ortak**: tüm personel aynı şişeleri canlı görür, her servisi kimin girdiği kaydedilir
- Dosya olarak açıldığında kayıtlar yalnızca o cihazda (localStorage) tutulur
- JSON yedeği kopyala / yapıştırarak yükle

## Kullanım
`index.html` dosyasını tarayıcıda açmanız yeterli — kurulum veya sunucu gerekmez.
