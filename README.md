# Amaç (Aim)
<img src="https://www.maxpixel.net/static/photo/1x/Phishing-Login-Password-Internet-Credentials-Data-6573326.png" data-canonical-src="https://www.maxpixel.net/static/photo/1x/Phishing-Login-Password-Internet-Credentials-Data-6573326.png" width="320" height="240" />
Özellikle Google arama sonuçlarında çıkan ve Türkiye'yi hedef alan her türden istenmeyen/spam, kimlik avı, kötü niyetli sitelerin bir listesini oluşturuyorum.
Bu listelerin büyük ölçüde sizi Google arama sonuçlarındaki zararlı sitelerden korumaya yardımcı olacağına inanıyorum.
<br><br>
Bu listelerdeki siteler güvenlik yazılımları tarafından <b>çoğunlukla fark edilmemiştir</b> ve <b>bu ihtiyaca binaen</b> oluşturulmuştur.

***

I am creating a list of all kinds of unwanted/spam, phishing, malicious sites that appear in Google search results and target Turkey.
I believe these lists will greatly help protect you from malicious sites in Google search results.

The sites in these lists are <b>mostly undetected</b> by security software and were created <b>for this need</b>.


# Listeler (Lists)
| Name | Raw link | Number of domains |
| ---- | :------: | :---------------: |
[Turkish Phishing List](https://github.com/yildizyan/hosts/blob/main/turkish-phishing-list) | [fly](https://raw.githubusercontent.com/yildizyan/hosts/main/turkish-phishing-list) | 54 |
[Turkish Spam List](https://github.com/yildizyan/hosts/blob/main/turkish-spam-list) | [fly](https://raw.githubusercontent.com/yildizyan/hosts/main/turkish-spam-list) | 16 |
[Turkish Bad Redirection List](https://github.com/yildizyan/hosts/blob/main/turkish-bad-redirection-list) | [fly](https://raw.githubusercontent.com/yildizyan/hosts/main/turkish-bad-redirection-list) | 106 |
[Turkish All in One List (recommended)](https://github.com/yildizyan/hosts/blob/main/turkish-all-in-one-list) | [fly](https://raw.githubusercontent.com/yildizyan/hosts/main/turkish-all-in-one-list) | 242 |

<i>Note: Turkish All in One List is updated before the others and covers them all.</i>
# Nasıl yapıyoruz?
Liste veya listelerden (tavsiye olarak hepsini kapsayan All in One listesinden) kullanacağınız platforma göre şu şekilde yararlanabilirsiniz:

Tarayıcı
---
Tarayıcıda kullanmayı düşünüyorsanız uBlock Origin eklentisiyle birlikte kullanmanız gayet efektiftir ve şiddetle tavsiye edilir. uBlock
Origin reklam ve izleyicileri engelleyen bir tarayıcı eklentisidir. Bu listeyi ona tanıtarak eksik kaldığı yanlarını bir anlamda
tamamlamış olursunuz.

uBlock Origin ayarlarına ulaşın. Filtre listeleri menüsüne tıklayıp en aşağı inin ve özel>içe aktar kısmına erişin. Oraya istediğiniz
filtrenin raw linkini yapıştırın ve değişiklikleri uygula talimatı verin. Bu kadar.

Windows
---
C:\Windows\System32\drivers\etc yolunda bulunan hosts dosyasına erişin. Masaüstüne kopyalayın ve not defteriyle açın. İstediğiniz listenin içeriğinini
tamamen kopyalayın ve not defteriyle açtığımız hosts'a yapıştırın. Hosts dosyasını önceki yaşadığı yere kopyalayın ve oradakiyle değiştirin. Listeyi arada güncellemeyi unutmayın.

Android
---
AdAway uygulamasını indirip yükleyin. Hosts source kısmından ilgilendiğiniz listenin raw linkini ekleyin. AdAway açık kaynak bir reklam engelleyici uygulamasıdır.
