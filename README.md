# generate_images_with_stable_diffusion

Bu notebook içerisinde KerasCV kullanarak verilen bir text'ten nasıl yüksek çözünürlü resim elde edebileceğimizi çalıştık.
Özellikle ekran kartlarınında gelişmiş olmasıyla kararlı difüzyonlar en yüksek verimi'ne 2022 ( XLA ve karmaşıklık hassasiyetini float16 veri tipinde kullanarak)
yılında ulaştı. 

Kararlı difüzyon kullanarak metinden görüntü elde etme adımları temel olarak 3 adımda gerçekleşir.
1-) giriş text'ini kullanıcıdan alırız ve vektöre dönüştürürüz.
2-) tamamen gürültüden oluşan bir girdiyle bu vektörü birleştiririz.
3-) elde edilen görüntüyü decoder'a vererek daha büyük ve gürültüden arındırılmış amaç görüntümüzü elde ederiz.

Kararlı difüzyonda yapılan işlemler sihirli gibi gelebilir ancak tabi ki de böyle bir durum söz konusu değildir.
Sadece çok fazla işlem var, sihir yok :)

Acaba beynimiz rüyaları kararlı difüzyon kullanan bir algoritma ile mi oluşturuyor.?
Acaba kararlı difüzyon kullanılarak farklı CNN görevleri için sentetik veri üretebilir miyiz? 

Aklınıza takılan herhangi bir soruda benimle iletişime geçmekten çekinmeyin.


 
