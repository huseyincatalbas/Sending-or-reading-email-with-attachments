# Eklentili E-Posta Gönderme veya Okuma / Sending or Reading E-mail with Attachments

## Eklentili E-Posta Gönderme / Sending E-mail with Attachments
Eklenti olarak resim olsun doküman olsun bunları text dosyası haline dönüştürebiliyoruz. Stringe dönüştürme işlemine encoding, tam tersine ise decoding işlemi denilmektedir. E-mail atarken aslında bir string objesi atıyoruz. Bu objeler çeşitli şekillerde değiştirilerek atılıyor. Sorunsuz şekilde kullanıcılara ulaştırılabiliyor.</br>
***As a plug-in, we can convert them into text files, whether images or documents. Stringe conversion process is called encoding, on the contrary, decoding. When sending e-mails, we actually throw a string object. These objects are changed and disposed of in various ways. It can be delivered to users without any problems.***

Çıktı olarak “{}” bu şekilde gözükmesi mesajın iletildiği anlamını taşımaktadır. Mail adresimi kontrol ettiğimdeki sonuç aşağıdaki resimde gösterdim.
***If "{}" looks like this as an output, it means that the message was transmitted. When I checked my e-mail address, I showed the result in the picture below.***

![image](https://github.com/huseyincatalbas/Sending-or-reading-email-with-attachments/blob/master/images/1.PNG)

## Gelen Kutusundaki Eklentili E-Postaları Filtreleyerek Okuma / Reading E-mails with Attachments in Inbox by Filtering
Buradaki yaptığım uygulama önceden “blur.jpg” isimli resim dosyası içeren bir mail atılmış olsun. Ancak mail sayımın fazla olmasından dolayı hangisi olduğunu bulamadığımı düşünelim. Yapacak olduğum uygulama ile maillerimi tarama işlemi yaparken “blur.jpg” resim dosyasına sahip olan kaç tane mail bulunuyorsa bunların dosya isimlerini, atıldığı tarih bilgisini ve mail başlıklarını listeleme işlemi yapacaktır.</br>
***Let me send a mail containing an image file named “blur.jpg” before the application I made here. However, let's think that I could not find which one because of the high number of mails. While scanning my e-mails with the application I will do, it will list how many e-mails that have a "blur.jpg" image file, their file names, date information and e-mails headers.***


## Sistem Gereksinimleri / System Requirements

* Anaconda Navigator

