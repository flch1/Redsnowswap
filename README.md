# hazırlık
npmjs sitesine üye ol, mail doğrulaması isterse yap. kullanıcı adını ve şifreni kenara not et.

```console 
https://www.npmjs.com/signup
```
# kurulum scripti bazı bilgiler isteyecek bunları önceden hazırla.
# kuruluma başlamadan önce bir proje ismi belirle, başka projelerle isim benzerliği olmaması için random sayı ya da benzersiz harfler eklemek sorun çıkmasını önler. mesela blacktea yaparsam benzeri çom olabilir ama blacktea024 ihtimalleri düşürür, blacktea024jdjdb yaparsam büyük ihtimalle böyle bir proje yoktur. bu isimi belirledikten sonra bu isimle bir repo aç.


# ssh key aşamasında oluşacak ssk key in public key kısmını github hesabına eklemeniz lazım. ayarlar/ssh and gpg keys e girince sağ üstlerde "new ssh key" butonuna basın, herhangi bir isim verin, public keyi ekleyin kaydete basın. public key hatasız girilmeli. tam olarak, boşluk bile bırakmadan,"ssh-rsa ile başlayıp uzun eşittire benzeyen işaretle '===' biten kısma kadar. (eğer mail adresini boş geçmediyseniz mail@mail.com gibi, .com kısmına kadar olmalı.) . ssh key githuba eklenmez, o kullandığınız bilgisayarda durmalı.


# proje anasayfası url si: "açtığın repoya giriş yaptığında tarayıcıdaki adres"
# proje url'si : "projenin içindeyken sağ üst kısımlarda code kutusunda https sekmesindeki sonu .git olan url, ssh değil http sekmesindeki"
# Description sorusuna projenin amacına dair bir şey ya da herhangi bir şey yazabilirsin
# author : "github kullanıcı adı"
# bu soruları birçok kez sorabilir her seferinde farklı dosyaları düzenlediği için.










# repoyu indir ve kuruluma devam et
```console
git clone https://github.com/flechemano/refill.git
```
```console
cd black-tea
```
```console
chmod +x kurulum.sh
```

```console
. ./kurulum.sh
```
