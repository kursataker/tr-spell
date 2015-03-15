## Introduction ##

Project for generating Hunspell compatible turkish spell checker packages (eg. Firefox spell checker). Same dictionary is used by Chrome after some modifications.

For a brief explanation how Firefox extension is produced check below link (Turkish O\_o)
http://zembereknlp.blogspot.com/2008/10/tr-spell-ve-firefox-turkce-imla-denetim.html

Please note that this project and extensions are NOT using zemberek project (a java library for simple Turkish morphological parsing) and algorithms. instead, it uses simple word lists with auto-generated affix information. it does not perform as good as zemberek library either. But because Hunspell is used in many places it is easier to integrate with other projects.

## Bilgi ##

Bu proje ile Huspell uyumlu turkce yazim denetimi dosyalarinin uretimi amaclanmistir (Ornegin Firefox Turkce yazim denetimi eklentisi). Google Chrome tarayicisi da bu dosyalari bazi degisikliklerden sonra kullanmaktadir.

Firefox eklentisinin nasil yapildigini anlatan bir blog girdisi:
http://zembereknlp.blogspot.com/2008/10/tr-spell-ve-firefox-turkce-imla-denetim.html

Bu projedeki imla denetim mekanizmasi zemberek kutuphanesini ya da algoritmalarini kullanmaz. Yazim denetimi Hunspell kutuphanesi ile gerceklestirilir. Proje basit kelime listesi ve otomatik olarak yapay ek bilgilerini uretir. Bu yazim denetim mekanizmasinin basarimi yapisal cozumleme tabanli Zemberek'e gore daha dusuktur.