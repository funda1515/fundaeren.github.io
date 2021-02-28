
# KALİ LİNUX KOMUTLAR VE PARAMETRELER



# ls Komutu

ls komutu aktif olarak girmek istediğimiz dosyanın veya dizinin listelenmesini sağlayan komuttur. Bu komut sayesinde klasörlerin veya dizinlerin içerisinde neler var görebilmekteyiz.



# Parametreler

## -l Parametresi

Bu parametre ile dizinimizde bulunan dosya ve dizinlerin bilgilerini sırasıyla dikey ve ayrıntılı olarak öznitelikleri, sahibi, grubu, boyutu, update tarihi, ve dosya isimleri olarak bilgi verilmektedir. 

![image](https://user-images.githubusercontent.com/55113204/109417828-4905a100-79d6-11eb-9e68-57eb21a064b2.png)


## -a Parametresi

Bir dosya veya dizini yatay olarak listeleyen ve ayrıntılı bilgi veren parametredir. Ve gizli olan dosya ve dizinleri de göstermektedir.

![image](https://user-images.githubusercontent.com/55113204/109418294-bca8ad80-79d8-11eb-9ced-f12872a8b117.png)

## -al Parametresi

-al parametresi gizli olan ve sadece ls komutu ile gösterilmeyen dosyaların listelenmesini ve yatay ve dikey olarak ayrıntılı bir bilgi vermesini sağlamaktadır. Sırasıyla öznitelikleri, sahibi, grubu, boyutu, update tarihi ve dosya isimleri hakkında bilgi vermektedir.

![image](https://user-images.githubusercontent.com/55113204/109418090-90d8f800-79d7-11eb-852c-8d1726c12433.png)

## -alrt Parametresi

Değiştirilme zamanlarına göre listeleme yapan parametredir.

![image](https://user-images.githubusercontent.com/55113204/109418204-27a5b480-79d8-11eb-97c6-90e78c5c1ea1.png)

## -l -h Parametresi

Hem kb,mb,gb gibi boyut değerleri ile hemde dikey ve ayrıntılı şekilde dosya veya dizin hakkında bilgi vermektedir.

![image](https://user-images.githubusercontent.com/55113204/109418226-4d32be00-79d8-11eb-8bec-0f744e6cd565.png)

## -o Parametresi

-h parametresi gibi dosya ve dizini listeleyen fakat boyutlarını göstermeyen, aynı zamanda farklı kullanıcı grubu olduğunda onları göstermeyen parametredir.

![image](https://user-images.githubusercontent.com/55113204/109418370-1c06bd80-79d9-11eb-87df-882ac0a67210.png)

## -l -t Parametresi

Dosya ve dizinleri dikey olarak ve time olarak listelemektedir. Son eklenen dosya veya dizin en üst sıradadır.

![image](https://user-images.githubusercontent.com/55113204/109418404-48223e80-79d9-11eb-8ab4-bc951d39950b.png)

## -l -t -r Parametresi

Burada zamana göre dikey ve ayrıntılı olarak listelenmektedir. Fakat reverse yani zamanı son eklenene göre değil ilk eklene göre listelenmektedir.

![image](https://user-images.githubusercontent.com/55113204/109418437-6f790b80-79d9-11eb-8140-73ca727224a6.png)

## -l -r Parametresi

Dosya ve dizini ayrıntılı olarak dikey olarak alfabetik olarak listeler ama reserve parametresi ile tersten sıralamaktadır.

![image](https://user-images.githubusercontent.com/55113204/109418504-bc5ce200-79d9-11eb-869d-bb95e2880789.png)

## -l -d Parametresi

Sadece bulunduğumuz dizin hakkında ayrıntılı bilgi vermektedir. Biz burada belgeler dizinindeyiz içindeki dosyaları görememekteyiz.

![image](https://user-images.githubusercontent.com/55113204/109418533-e1e9eb80-79d9-11eb-8251-a4ba338c8479.png)

## -l listelenmek_istenen1 listelenmek_istenen2 Parametresi

İki veya daha fazla dizini aynı anda dikey ve ayrıntılı olarak listeleyebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109418551-fc23c980-79d9-11eb-8fa2-c6c331efdc5a.png)

## -i Parametresi

Dosyaların index bilgilerini küçükten büyüğe doğru sıralamaktadır.

![image](https://user-images.githubusercontent.com/55113204/109418558-1198f380-79da-11eb-94eb-111687840458.png)

## --sort=? Parametresi

Sıralama soru işareti yazılan yere gelen parametreye göre büyükten küçüğe göre yazılır. Extension, size, time, version veya none olarak değerler yazılabilir.

![image](https://user-images.githubusercontent.com/55113204/109418585-3e4d0b00-79da-11eb-9d27-478e2b42c7eb.png)

## -I ? Parametresi

Soru işareti ile belirtilen alana gösterilmesini istemediğimiz klasörü yazdığımızda ayıklayarak listeliyoruz.

![image](https://user-images.githubusercontent.com/55113204/109418611-60df2400-79da-11eb-8e9e-5c804ea93f0f.png)

## -R Parametresi

Alt dizinleri listelemektedir.

![image](https://user-images.githubusercontent.com/55113204/109418626-75bbb780-79da-11eb-9698-8d50179279f0.png)

## -1 parametresi

Her satıra 1 dosya yazılarak listeleyen komuttur.

![image](https://user-images.githubusercontent.com/55113204/109418635-83713d00-79da-11eb-9f9d-144593f4b9ec.png)

## - -v Parametresi

Version bilgilerini göstermektedir.

![image](https://user-images.githubusercontent.com/55113204/109418647-9be15780-79da-11eb-8d2e-4880b0c986d4.png)

## - -help Parametresi

ls komutu ile ilgili daha fazla bilgi edinmek için help komutu kullanılmaktadır.

![image](https://user-images.githubusercontent.com/55113204/109418657-b3b8db80-79da-11eb-8abc-8fa58581ba26.png)



# whoami Komutu

Ben kimim komutudur. Who am i yani aktif user kim onu gösterir. Bu komut yerine id -un komutu da kullanılabilmektedir. Burada biz kullanıcının funda olduğunu görmekteyiz.

![image](https://user-images.githubusercontent.com/55113204/109419299-c8e33980-79dd-11eb-9d5f-50dd83fcb4de.png)

# tar Komutu

Arşivleme yapan komuttur. Burada -c parametresi ile tar arşivini create eder. -f ile de izin verir.

![image](https://user-images.githubusercontent.com/55113204/109419322-e31d1780-79dd-11eb-8116-b6e65217b076.png)

-x parametresi var olan arşivi aç
-t parametresi tar arşivinin içeriğini listele
-v parametresi kullanıcıya neler olduğunu anlat
-r parametresi arşivi addle
-u parametresi arşivi updatele
-z parametresigzip/gunzip kullanarak sıkıştırma yap
-remove parametresi arşivle işin bitince sil

# Gzip/guzip Komutu

Dosyaları gziple ve guziple arşivler.

![image](https://user-images.githubusercontent.com/55113204/109419343-0051e600-79de-11eb-87a7-9737b91a5357.png)

-l parametresi sıkıştırılmış dosyanın içeriğini listeleler.
-f parametresi dosyalar açılırken benzerleri varsa üstüne yazar.

![image](https://user-images.githubusercontent.com/55113204/109419347-09db4e00-79de-11eb-8440-06f3c9c1ca52.png)

# apropos Komutu

bBir komutun ne işlev yaptığını bilindiği ama komutun ne olduğunu unuttuğumuzda apropos komutu kullanılır. Misal sistemin ne olduğunu biliyorum ama ne işe yaradığını bilmiyorsam burada apropos komutu kullanabilirim.

![image](https://user-images.githubusercontent.com/55113204/109419373-2b3c3a00-79de-11eb-8178-62b50c192cce.png)

# cat Komutu

Bir metin dosyasının içerisinde neler var onları görüntülemek için kullanılan komuttur.

## -n Parametresi 

-n parametresi ile her satırı ekrana bastırır.

![image](https://user-images.githubusercontent.com/55113204/109419417-6b032180-79de-11eb-902e-dda8ed623941.png)

## -E Parametresi

-E parametresi ile her satırın sonuna $ işareti koyar.

![image](https://user-images.githubusercontent.com/55113204/109419439-83733c00-79de-11eb-878e-5ecd03f29037.png)

# mkdir Komutu

Dizin yani klasör oluşturma komutudur. Biz burada fundaa isimli bi dizin oluşturduk ve -ls komutu yardımı ile görüntüledik. 

![image](https://user-images.githubusercontent.com/55113204/109419463-9f76dd80-79de-11eb-9cdb-e0327c664722.png)

# cp Komutu

Copy paste yani bir dosyayı yada klasörü kopyalamak istenildiğinde kullanılan komuttur. 
-r parametresi ile kullanılır sebebi ise dizinin içindeki her şey gösterilen hedef dizine kopyalanır. funda_deneme isimli dizini bulunduğu konumdan belgelere kopyaladım.

![image](https://user-images.githubusercontent.com/55113204/109419499-d51bc680-79de-11eb-9cc2-d2f40a10cd0e.png)

-d paratmetresi dosyanın aslını değil linkini kopyalamaktadır.
-p parametresi ile dosyanın kullanıcı izinlerini ve passwordlarını koruyarak kopyalanmasını sağlamaktadır.
-a parametresi diğer parametrelerle aynı kullanımdadır.
-f parametresinde kullanıcıya hiçbir izin sorusu sorulmadan kabul edilmiş olarak düşünülerek varsa aynı dosyadan silinip tekrardan kopyalanmasını sağlayan değerdir.
-i hedef adreste dosya mevcut ise kullanıcıya bilgi sorulur.
-u parametresinde kopyalanacak dosyanın tarihi eski dosyadan daha yeni ise bir nevi güncel ise kopyalanmaktadır.
# cat Komutu

Cat komutu ile dosya oluşturulup dosya içeriği okunabilmektedir. Text ve script dosyalarını okuyabilmemizi sağlamaktadır. Burada deneme adında bir dosya oluşturduk ve dosyanın içine Ankara ve Istanbul isminde iki bilgi girdik. Cat komutu ile hem dosyayı oluşturabildik hemde içeriği görüntüleyebildik.

![image](https://user-images.githubusercontent.com/55113204/109419537-ff6d8400-79de-11eb-8aa0-27f2a2fb3fb5.png)

Cat ile dizinlerin içine girmeden direk home üzerinden istenilen hedefe dosya oluşturulabilir.

![image](https://user-images.githubusercontent.com/55113204/109419542-085e5580-79df-11eb-8af5-83daf27a27d3.png)

Cat ile bir dizinin sonuna ekleme yapılarak update yapılabilir.

![image](https://user-images.githubusercontent.com/55113204/109419546-0f856380-79df-11eb-81d6-f92389f8962f.png)

Cat komutu ile iki dosya farklı bir dosyada birleştirilme yapılabilir. Burada dosya1 ve dosya2 isminde iki tane dosya oluşturdum. Içine yazdığım bilgilerin birleştirmek için dosya3 adında dosya oluştururak görüntüledim.  E harfinden sonra boşluk bırakmadığımdan dolayı f harfiyle birleşti. Burada dosya birleştirdiğimizden dolayı arka arkaya geldiğini görmekteyiz
Satır numaraları ile görüntülemek için -n parametresi kullanmaktayız.

![image](https://user-images.githubusercontent.com/55113204/109419591-465b7980-79df-11eb-96b1-76b24a174486.png)

Dizinlerin içindeki tüm içerikleri görmek için “*” kullanılmaktadır.

![image](https://user-images.githubusercontent.com/55113204/109419604-5d9a6700-79df-11eb-87ec-46884a4e179b.png)

Cat hakkında daha fazla bilgi almak için - - h parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109419610-67bc6580-79df-11eb-8d94-805f67a70849.png)


# Mv Komutu

Mv komutu move yani taşıma yapmaktadır. Öncelikle taşınacak bir dosya oluşturuyoruz ki daha kolay anlayabilelim. Taşınacak yer adında bir dosya oluşturuyoruz. Dosyamızı buraya taşıyacağız sonra taşınıp taşınmadığını kontrol edelim.

![image](https://user-images.githubusercontent.com/55113204/109420954-4b6ff700-79e6-11eb-8b17-47eb0ddf7e21.png)

Tabi bunları yaparken hedef dizinde aynı isimde dosya var mı yok mu kontrol edilmelidir. Bu kontrol -i parametresi ile yapılmaktadır. Eğer aynı isimde bir dizin mevcut ise üzerine yazılsın mı diye bizden onay beklemektedir.

![image](https://user-images.githubusercontent.com/55113204/109420966-5d519a00-79e6-11eb-8e1b-b338da6866ac.png)
 
Mv komutu ile bir dosyanın uzantısını değiştirebiliriz. Masaüstünde bulunan fundaa isimli klasörü fundaa.txt metin dosyasına dönüştürebiliriz. Taşıma işlemi gibi önce değiştirilecek klasör ve sonra hangi tipe dönüştüreceğimizi belirleyip uzantısını ekleyerek yapmaktayız. Bu şekilde dosyanın adını da değiştirebiliriz. 

![image](https://user-images.githubusercontent.com/55113204/109420968-66426b80-79e6-11eb-89e2-c917a30c79a2.png)

## -n Parametresi

var olan dosyanın üzerine sorulmadan yazılmasını sağlamaktadır. Dosya taşındıktan sonra eski yerinden tamamen kaybolmuştur. Burada belgeleri masaüstüne taşıdık ve tekrar listelediğimizde taşındığını görmekteyiz.

![image](https://user-images.githubusercontent.com/55113204/109420984-765a4b00-79e6-11eb-9dc7-cecd585207ed.png)

# touch Komutu

touch komutu ile sıfır boyutlu dosya oluşturabiliriz. Burada kali isminde dosya oluşturduk.

![image](https://user-images.githubusercontent.com/55113204/109421013-8d993880-79e6-11eb-8ffa-ebc601dd6001.png)

Dosyaların isimlerini yan yana yazarak birden fazla dosya da oluşturabiliriz.

![image](https://user-images.githubusercontent.com/55113204/109421029-9c7feb00-79e6-11eb-948c-70c321398bff.png)

# stat Komutu

Bu komut sadece dosya adı ile dosyanın bilgilerini görüntülenmesini sağlamaktadır.

![image](https://user-images.githubusercontent.com/55113204/109421044-ab669d80-79e6-11eb-8deb-29074c05d48d.png)

# alias Komutu

Takma isim oluşturan komuttur. Isim = değer şeklinde syntax vardır.

![image](https://user-images.githubusercontent.com/55113204/109421058-bc171380-79e6-11eb-92fd-d40f225d6f55.png)

Kali de zip işlemi ziplenecek yer ve dosya olarak yazılır.

![image](https://user-images.githubusercontent.com/55113204/109421068-cdf8b680-79e6-11eb-9faa-5637e8797ef0.png)

Ziplediğimiz dosyanın içine -r parametresi ile özyinelemeli olarak yeni dizin ekleyebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109421075-d9e47880-79e6-11eb-8ce4-e3956667b33c.png)

Cat komutu ile zipin içine bakalım.

![image](https://user-images.githubusercontent.com/55113204/109421081-e1a41d00-79e6-11eb-9d72-80031286a16a.png)

Unzip komutu ile zip olan bir dosyayı çıkartabiliyoruz.

![image](https://user-images.githubusercontent.com/55113204/109421085-e8cb2b00-79e6-11eb-9d80-4a0281069fd4.png)

-d parametresi ile farklı lokasyona zip dosyasını çıkartabiliyoruz.

![image](https://user-images.githubusercontent.com/55113204/109421091-ef59a280-79e6-11eb-9e30-0549a8824f35.png)

# chmod Komutu

Yetkilendirme izinleridir. Üç tip kullanıcı vardır u (user), g (group), o (other) olmak üzere bir de a (all) hepsini erişebilen bir kullanıcı vardır. Bunların yetkilendirilme tiplerine göre r (read), w (write) ve x (excute) olmak üzere 3 tür mevcuttur. Burada d dizinin de user rwx yani read,write,execute yetkisine, group xr (excute, read) yetkisine ve other x (excute) yetkisine sahiptir. ‘-’ tamamen yetkisiz olduğunu göstermektedir. D burada dizini temsil etmektedir. B özel blok sayfasını, c özel karakter dosyasını, l sembolik bağlantı dosyasını ve p ise özel isimlendirilmiş pipe dosyasını belirtmektedir. 

![image](https://user-images.githubusercontent.com/55113204/109421111-04cecc80-79e7-11eb-81d3-d05d1c22c475.png)

Chmod izinleri harflerle olduğu gibi rakamlar ile de gösterilebilir. r =4, w=2, x=1 değerlerine eşittir. Binary olarak da gösterilebilmektedir. Örneğin 010 okuma yok, yazma var, çalıştırma yok anlamına gelmektedir.
Yetkilendirme izin örneği verecek olursak masaüstü dizininde drwxr-xr-x şeklinde yetkilendirilme verilmiş. Biz burada sadece user tüm yetkilere sahip olsun istiyoruz ve diğerlerinin tüm yetkilerinin kaldırılmasını istiyoruz. Bunun için oluşturmamız gereken komut ‘ chmod u=rwx,go= Masaüstü ’ şeklindedir.

![image](https://user-images.githubusercontent.com/55113204/109421118-0d270780-79e7-11eb-90b2-e831fbaac57d.png)
![image](https://user-images.githubusercontent.com/55113204/109421123-131ce880-79e7-11eb-9d41-376322f647ad.png)

‘*’ parametresi ile dosyaya tüm kullanıcıların okuma erişimi sağlanmaktadır.

# ssh Komutu

Ssh ile bağlantı kurulurken önce kurulacak bilgisayarın rootu (whoami ile bulunuyor) daha sonra ip adresi (ifconfig ile bulunuyor) ssh root@ipadress komutu kullanılarak yazılır. Burada iki makinede ssh açık olmalıdır. Uzaktan bağlantı sağlamak için bağlanmak istediğimiz makinenin password girip connection sağlayabilmekteyiz. 

![image](https://user-images.githubusercontent.com/55113204/109421160-42335a00-79e7-11eb-9fd5-24a2d9fed1e7.png)

# cksum Komutu

Bir dosya veya veri akışı için sağlama toplamı değerini veren komuttur. İlk sayı sağlamada toplam değerdir, ikincisi ne kadar büyüklüğe sahip olduğu ve son kısım ise dosyanın adıdır.

![image](https://user-images.githubusercontent.com/55113204/109421190-5e36fb80-79e7-11eb-9826-c3c9f88f777c.png)

İçerisine bir yazı yazdığımda değeri değişecektir.

![image](https://user-images.githubusercontent.com/55113204/109421201-6727cd00-79e7-11eb-90df-79c816cf71c1.png)

# History Komutu

Daha önce kullandığımız komutları görmek istediğimizde bu komut kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109421422-4ca22380-79e8-11eb-89a7-365dec33b667.png)

History -c ile geçmişi temizleyebilir yada son 5 kullanılmış komutları görüntülemek için history -5 gibi değerler yazılabilir. Grep komutunu kullanarak ise tüm history listelemek yerine istediğimi komutu görüntülemekteyiz. 

![image](https://user-images.githubusercontent.com/55113204/109421428-53c93180-79e8-11eb-9ae3-7d6aa887b72b.png)

Bir komutu tekrar yazıp çalıştırmak yerine history üzerinde işlenmiş sayı numarasına göre “!” ile tekrar komutu çalıştırabiliriz. Misal olarak 74. Satırda cd Masaüstü var ve ben !74 yazarak masaüstüne geçiş yapabildim.

![image](https://user-images.githubusercontent.com/55113204/109421455-6e9ba600-79e8-11eb-9e15-feb64370d693.png)

# Cut Komutu

Bu komut bir dosya veya dizinde belirli bir kısmı almak istediğimizde kullanılır. Ilk olarak -c kullanımı görelim. Burada 5. Biti ekrana bastırılır.

![image](https://user-images.githubusercontent.com/55113204/109421470-8115df80-79e8-11eb-9633-07fdcad4cb65.png)

Belirli aralıktaki içerikleri de alabiliyoruz.

![image](https://user-images.githubusercontent.com/55113204/109421478-883ced80-79e8-11eb-9e73-e15a74377ff9.png)

Belirli baytları göstermesi için -b parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109421501-a60a5280-79e8-11eb-8ce1-16821e4a6399.png)

Satırlardaki istenilen değer kadar kesilip listelenebilir.

![image](https://user-images.githubusercontent.com/55113204/109422046-f7b3dc80-79ea-11eb-86ec-88be86c26797.png)

5. bitten sonrasını görmek istediğimizde de şu şekilde gösterebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109422079-174b0500-79eb-11eb-8417-ee6939d8c5dd.png)

-f parametresi uzunluğu çok fazla olan söz dizilimlerini kesmek için kullanılır.

# date Komutu

Tarih saat bilgisini ayarlamamızı, lokasyon değişikliğine göre güncellememizi yeniden yapılandırmamızı sağlayan komuttur.

![image](https://user-images.githubusercontent.com/55113204/109422093-292ca800-79eb-11eb-9e3b-e806321d6cdf.png)

Zone değişikliğinde lokasyonu setleyebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109422104-334ea680-79eb-11eb-9e09-ce19e607a6f8.png)

# df Komutu

Diskteki boş alanı, ne kadar boş alan olduğunu mount (bağlanma noktasını), doluluğunu, kullanılan alanın boş alana oranı, blok sayısını gösteren komuttur.

![image](https://user-images.githubusercontent.com/55113204/109422130-45304980-79eb-11eb-9c4f-f0aa9262d959.png)

## -a Parametresi

-a paremetresi ile daha ayrıntılı bilgi almaktayız.

![image](https://user-images.githubusercontent.com/55113204/109422135-4cefee00-79eb-11eb-9ba7-27db39bcdb03.png)

## -h Parametresi

Dosyanın boyutu hakkında bilgileri gb cinsinden görmek için -h parametresi,

![image](https://user-images.githubusercontent.com/55113204/109422147-5e38fa80-79eb-11eb-9ae8-661b3ffd98f3.png)

## -i Parametresi

Dosyanın inodesi hakkında bilgilere ulaşmak için -i paremetresi,

![image](https://user-images.githubusercontent.com/55113204/109422154-67c26280-79eb-11eb-82df-a6de0b032fed.png)

## -T Parametresi

Dosyanın tipleri hakkında bilgi edinmek istenilirse -T paremetresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109422202-9cceb500-79eb-11eb-83fc-9123d4e61020.png)

## -m Parametresi

Dosyanın mb cinsinden bilgilerine ulaşılmak istenirse -m parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109422217-ace69480-79eb-11eb-9050-b15ebbc505c8.png)


# fdisk -l Komutu

Sistemdeki diskleri ve bölümlerini listelemek için kullanılan komuttur.

![image](https://user-images.githubusercontent.com/55113204/109422237-c4be1880-79eb-11eb-9bd0-755eea1c4a59.png)

-d parametresi ile disk üzerinde bir bölümü silmek yada biçimlendirmek için kullanılır.
-n parametresi yeni bir disk oluşturur.

# diff Komutu

Difference yani faklılıkları karşılaştıran bir komuttur. -a parametresi ile birlikte kullanıldığında metin dosyası olarak karşılaştırma yapmaktadır.

![image](https://user-images.githubusercontent.com/55113204/109422317-2088a180-79ec-11eb-905b-9767ff0dbadc.png)

6c2 burada 6. Satır ile 2. Satır eşleşmesi için değiştirilmesi gerekiyor.
D ise birinci dosyadaki satır ikinci dosyadaki satırla eşleşecek şekilde silinmelidir. Burada hat 0 sekronize hale gelmesi için ilk dosyadan silinöesi gerek 2 satıra ihtiyaç vardır denilmektedir.

## -r Parametresi

-r parametresi ile varsa alt dizinleri karşılaştırır. 

## -q Parametresi

İki dosyanın birbirinden farklı olduğunu öğrenmek için -q parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109422384-56c62100-79ec-11eb-822f-37f29dfa0cd8.png)

## -s Parametresi

-s parametresi ile aynı olan dosyaları öğrenmek istediğimiz de kullanırız.

# du Komutu

Du disk kullanımının ne kadar yer kapladığını gösterir. 

![image](https://user-images.githubusercontent.com/55113204/109422417-7b21fd80-79ec-11eb-9f6e-9d7ba204b6ec.png)

## -a Parametresi

-a parametresi içindeki dizinlerin ayrıntılı olarak yer kaplamasını gösterir.

![image](https://user-images.githubusercontent.com/55113204/109422430-85dc9280-79ec-11eb-93b2-81e4a2083ff2.png)

## -c Parametresi

-c parametresi toplam ne kadar disk kullandığını gösterir.

![image](https://user-images.githubusercontent.com/55113204/109422442-912fbe00-79ec-11eb-9a79-eddb368eda9f.png)

## -BG Parametresi

-BG kullanıcıların daha açık bir şekilde anlaması için boyutu gösteren parametredir.

![image](https://user-images.githubusercontent.com/55113204/109422463-ab699c00-79ec-11eb-8843-cec7eabab476.png)

## -ca Parametresi

-ca disk kullanımını ayrıntılı gösteren parametredir.

![image](https://user-images.githubusercontent.com/55113204/109422472-b9b7b800-79ec-11eb-8d91-cfb3ca1e527f.png)

_du -sh .[!.]* * | sort -n parametreleri ile gizli olan dosyaları boyutları ile birlikte göstermektedir._

![image](https://user-images.githubusercontent.com/55113204/109422492-d0f6a580-79ec-11eb-9f16-d8a0395fcc7a.png)

# less Komutu

Bu komut dosyanın içeriğini görüntülememizi sağlamaktadır.
Kullanımı less dosya şeklindedir.

![image](https://user-images.githubusercontent.com/55113204/109422509-e66bcf80-79ec-11eb-8f3b-d944a0dd90fd.png)

# more Komutu

Sayfayı görüntülememizi sağlayan komuttur. Less komutu gibidir.
More -p parametresi ile kullanıldığında önce sayfayı temizler daha sonra görüntüler.

![image](https://user-images.githubusercontent.com/55113204/109422529-f388be80-79ec-11eb-913b-b042ecbd15a4.png)

## -s Parametresi

-s parametresi birden fazla boş satırı tek boş satır olacak şekilde sıkıştırma yapar.

![image](https://user-images.githubusercontent.com/55113204/109422535-ff748080-79ec-11eb-9f8c-e6ec85706802.png)

## -n Parametresi

-n parametresi ile dosyayı satır satır yazar.

## -f Parametresi

-f parametresi ile dosya ismini ve satır numarasını gösterir.

# echo Komutu

Echo ile hangi kabukta olduğunu görmek istiyorsak echo $SHELL komutunu bastırırız.

![image](https://user-images.githubusercontent.com/55113204/109423142-68f58e80-79ef-11eb-8ee3-0e539e385f31.png)

Echo ile ekrana yazı bastırabiliriz.

![image](https://user-images.githubusercontent.com/55113204/109423146-701c9c80-79ef-11eb-9bb2-e4e2c790d7b9.png)

Echo ile yeni bir dosya oluşturabiliriz.

![image](https://user-images.githubusercontent.com/55113204/109423165-8591c680-79ef-11eb-9805-a4dbac0ed88b.png)

Echo ile hem yeni dosya oluşturup hem de içini doldurabiliriz.

![image](https://user-images.githubusercontent.com/55113204/109423173-8b87a780-79ef-11eb-8c79-47a8dc8d7125.png)

Dosyamızı güncelleyebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109423175-92161f00-79ef-11eb-9eb0-37fc5c9ed48c.png)

Echo kullanarak matematiksel işlemleri ekrana bastırabiliriz.

![image](https://user-images.githubusercontent.com/55113204/109423181-99d5c380-79ef-11eb-85ee-703cc73265b4.png)

# locate Komutu

Hızlı olarak arama komutudur. Bir dosyanın nerde olduğunu unuttuğumuzda locate komutu ile dosyanın adını yazarak arama yapmaktayız.

![image](https://user-images.githubusercontent.com/55113204/109425871-8d576800-79fb-11eb-88ba-82335a0844b1.png)
 
 ## -i Parametresi
 
-i parametresi ile kullanıldığında büyük küçük harfleri sorun etmeden arama yapmaktadır.

# wc Komutu

Bu komut sırasıyla satır sayısı, kelime sayısı ve komut sayısını ekrana bastırmaktadır.

![image](https://user-images.githubusercontent.com/55113204/109425877-934d4900-79fb-11eb-8ed6-f5831c3b70b2.png)
 
## -c Parametresi

Karakter sayısını ekrana bastırmak için -c parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109425882-98aa9380-79fb-11eb-86d9-e5f6ea10aed2.png)
 
## -w Parametresi

Kelime sayısını göstermek için -w parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109425889-9ea07480-79fb-11eb-9bbd-e1fa43e3eefa.png)

## -l Parametresi

Satır sayısını göstermek için -l parametresi kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109425891-a3652880-79fb-11eb-84c5-2aa3b208246f.png)

# env Komutu

Environment komutu systemin propertiesi hakkında bilgi veren komuttur.

![image](https://user-images.githubusercontent.com/55113204/109425900-a9f3a000-79fb-11eb-8057-f30c29496b98.png)

# expand Komutu

Girdi de verilen tab değerini space değerine çevirme işlemi yapmaktadır.

![image](https://user-images.githubusercontent.com/55113204/109425907-aeb85400-79fb-11eb-8275-bd4b80865462.png)

# free Komutu

Bir işletim sisteminde belleğin ne kadarının kullanıldığı ve ne kadarının boş olduğunu göstermeye yarayan komuttur.

## -h Parametresi

-h parametresi kullanarak çıktımızı daha anlamlı hale çevirebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109425911-b5df6200-79fb-11eb-936b-c5c934d58b38.png)

Burada takas ve memory kullanımını görebilmekteyiz. Ne kadarının paylaşıldığını ne kadarının meşgul olduğunu total de ne kadarlık belleğe sahip olduğumuzu görmekteyiz.

# ps Komutu

Ps komutu o anda çalışan işlemleri gösteren komuttur.

## -A Parametresi

-A parametresi kullanarak çalışan tüm işlemler gösterilmektedir.

![image](https://user-images.githubusercontent.com/55113204/109425975-18386280-79fc-11eb-97f6-549a8e7ad866.png)

## -ax Parametresi

-ax parametresi kullanılarak o anda çalıştırabilir tüm işlemler gösterilmektedir.

![image](https://user-images.githubusercontent.com/55113204/109425979-1c648000-79fc-11eb-94bf-d8934ca0192f.png)

## -aux Parametresi

Ps aux parametresi kullanılarak daha simple şekilde gösterilmektedir.

![image](https://user-images.githubusercontent.com/55113204/109425983-24242480-79fc-11eb-8cdc-f58a6c9d34a7.png)
 
## -L [istenilen_satır] Parametresi

Bu parametre ile istenilen satır hakkında detaylı bilgi edinilmektedir.

![image](https://user-images.githubusercontent.com/55113204/109425988-2a1a0580-79fc-11eb-8776-327b47444a68.png)

## -C Parametresi

-C bash parametresi çalıştırılan bash işlemleri hakkında bilgi vermektedir.

![image](https://user-images.githubusercontent.com/55113204/109425995-2e462300-79fc-11eb-9e84-3f2c94b92acc.png)

## -U root -u root Parametresi
 
Çalıştırılmış root işlemleri hakkında bilgi almak istediğimizde -U root -u root parametresini kullanmaktayız.

![image](https://user-images.githubusercontent.com/55113204/109425997-32724080-79fc-11eb-8210-cd3dd9fa4790.png)

## -e Parametresi
 
-e parametresi sistemde çalışan her süreç hakkında bilgi verir. 

## -u Parametresi

-u kullanıcı adına göre süreç bilgilerini verir.

## -p Parametresi

-p süreç numaralarına göre (PID) süreç bilgisi verir.


# pstree Komutu 

Süreci hiyerarşik olarak görüntülemek istersek bu komutu kullanırız. Bir ağaç gibi bize ayrıntılı anlatmaktadır. 
 
 ![image](https://user-images.githubusercontent.com/55113204/109426000-3b631200-79fc-11eb-95fe-876592d1ba05.png)

# top Komutu

Bu süreci 3 saniyede bir yenilerek sistemin anlık sürecini bilgi verir. -d saniye parametresi şeklinde yazarak anlık güncellenen süreyi değiştirebiliriz. Q ile çıkış yaparız.

![image](https://user-images.githubusercontent.com/55113204/109426004-3f8f2f80-79fc-11eb-86e4-ffe5fa7c19be.png)























1. Numbered
2. List

**Kodlar anlatılabilir** and _italik yazı tipinde kullanım sağlanabilir_ and `Code` text

[Link](url) and ![Image](src)
```

Daha fazla detay vermek için benzeri sitelere yönlendirebilirim [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/ yönlendireceğim site uzantısı hakkında bilgi).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/funda1515/fundaeren.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
