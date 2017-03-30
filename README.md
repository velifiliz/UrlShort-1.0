<snippet>
  <content><![CDATA[
# ${1:Project Name}

.NET ile Yazdığınız Projelerinizde Url Kısaltma İşlemlerinizi Yapmak İçin Kullanabileceğiniz Kütüphanedir.

## Kurulum

İndirdiğiniz shorturl.plugin.dll Dosyasını Projenize Dahil Ediniz.

## Kullanım
 
Kütüphanemizde 1 Adet Metod Bulunmaktadır.

1.Metod Twitlerinizi JSON Türünde Geriye Döndürür.

        var u = plugin.url.send("http://shop.samsung.com/tr?utm_source=google&utm_medium=search&utm_campaign=pre-order&gclid=CL3ljdWA_dICFfgV0wodqBwC7w");
            MessageBox.Show(u);
