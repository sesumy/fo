#  Düzenli İfadeler

.fx: first
 



***Nisan 2016***


***Sedat AKLEYLEK***

-------

##  Sunumu Hazırlayanlar 
.fx: first 

Ayşe Berika VAROL `<berika.varol@bil.omu.edu.tr>`

Hafsa ULUSAL `<hafsa.ulusal@bil.omu.edu.tr>`

Hatice GÜNEŞ `<hatice.gunes@bil.omu.edu.tr>`

Neşe Ayşen AKGÜN `<aysen.akgun@bil.omu.edu.tr>`        

Sinem Aybike HÜR `<aybike.hur@bil.omu.edu.tr>`

Sümeyye SEVİNÇ `<sesumy@bil.omu.edu.tr >` 

## Konu Akışı 

-        Düzenli İşlemler ve Düzenli İfadeler
-        Sonlu Otomatanın Denkliği
-        Sonlu Otomatanın Denkliği Soru Çözümü
-        Pumping Lemma
-        Pumping Lemma Soru Çözümü-1
-        Pumping Lemma Soru Çözümü-2
-        ***QUIZ***
## Düzenli İşlemler ve Düzenli İfadeler
.fx: first

***12060394***

***Sümeyye SEVİNÇ***

##Düzenli İşlemler

-       Sonlu otomatalar tarafından kabul edilen diller sınıfı aşağıdaki özelliklere sahip olmalıdır.
</br>
    - Birleşme (Union)

    - Birbirine Bağlama (Concatenation)

    - Yıldız (Kleene star)


## 
**Örnek**
       

        ∑={s,m,y,v,n,c} A={s,m,y} B={v,n,c}

-        Birleşme Özelliği:

	A U B = {x| x ∈ A veya x ∈ B } olacak şekilde 

	A U B ={s,m,y,v,n,c}	

-        Birbirine Bağlama :

	A o B = {xy| x ∈ A veya y ∈ B }

	A o B ={sv,sn,sc,mv,mn,mc,ys,yn,yc}

-        Yıldız:

	A*= {x,x1,x2....xk , k≥0} olacak şekilde
 
	A*={ø,s,m,y,sm,sy,my,smy..}    

##Düzenli İfadeler

-        Bir ifadenin düzenli olabilmesi için aşağıdaki şartlar sağlanmalıdır.

    - R = {a | a ∈ ∑} //∑ =Alfabe

    - R = {Ø}  //Boş küme

    - (R1 U R2), (R1 o R2), R1*  // Düzenli işlemler uygulanabiliyor ise R1 ve R2 düzenli

    - R = {ε}  //Boş kelime

##Örnek

-        {a,b,c,d} ve {0,1} oluşan düzenli ifademizde 

     - a(b U c) ==> {ab, ac}

     - ab* ==> {a, ab, abb, abbbb, ...}

     - (0 U 1)* ==> {ε, 0, 1, 00, 01, 10, 11, ...}

     - a(b U cd*)*a ==> {aa, aba, acda, acdda, ...}

##Düzenli İfade Özellikleri

-         R U Ø = R       //R kümemiz boşluk ile birleştirilirse kendine eşit olabilir.

-         R o ε = R       //R kümemiz boş kelime ile birbirine bağlanırsa kendine eşit olabilir.

-         R U ε =! R      //R kümemiz boş kelime ile birleştirilirse kendine eşit olmayabilir.

-         R U ε = {R, ε}  //R kümemiz boş kelime ile birleşirse ya kendine yada boş kelimeye eşit olabilir. 

-         R o Ø =! R      //R kümemiz boş küme ile birbirine bağlanırsa kendine eşit olmayabilir.

-         R o Ø = {Ø}     //R kümemiz boş küme ile bağlanırsa boş kümeye eşit olur.

-         R = 0 = {0}   //R kümemiz boşluğa eşit ise boş kümedir.

## Sonlu Otomatanın Denkliği
.fx: first

***12060366***

***Hafsa ULUSAL***
  
## Sonlu Otomatanın Denkliği 
-        Düzenli bir dil bazı sonlu otomatalar tarafından tanımlanır.

Teorem:

-         Bir dilin düzenli ifade olabilmesi ancak ve ancak bazı düzenli ifadelerin onu tanıması ile mümkündür.

-         Elimizdeki düzenli bir ifadeyi NFA ya dönüştürmek için düzenli ifadenin 6 formal durumu (düzenli ifade olma) içermesi gerekmektedir.
## Durumlar

-        Teorem:Eğer R düzenli bir ifade ise L(R) düzenli bir dildir.

-        Durum 1: R={a | a ∈ ∑}

    - L(R)={a}

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/durum1.png)

##

-        Durum 2:R=ε 

     -   L(R)={ε}
![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/durum2.png)



-       Durum 3:R=Ø

    -   L(R)= Ø 

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/durum3.png)

##

-        Durum 4=R=R1 ∪ R2
     
     - NFA'da tanımlı R1 ve R2 oluşturulur.

     - L(R1  ∪ R2) = L(R1) ∪  (R2)

-       Durum 5=R=R1◦R2

     - NFA'da tanımlı R1 ve R2 oluşturulur.

     - L(R1  ○ R2) = L(R1) ○ (R2)

-      Durum 6:R1=(R1)*

     -  NFA'da tanımlı R1 oluşturulur.

     -  L(R1*) = (L(R1))*

##Örnek
-       a*b* düzenli ifadesini NFA formuna dönüştürünüz.

Genellikle yapılan hatalı çizim ;

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/ornek11.png)

-       Yukarıdaki şekilde anlatılmak istenen tek bir durum(state) oluşudur ve bu durum hem başlangıç hem de bitiş durumu olarak tanımlanmıştır.Bu durum üzerinde hem a hem de b istenildiği kadar dönebilir.Fakat sonlu durum makinesi hatalıdır bunun sebebi ba gibi bir kelimeyi kabul etmesidir.

##

-        Örnek çizim;

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/ornek12.png)

-        Yukarıdaki çizim hem boş kelimeyi hem de a ve b ile üretilebilecek bütün kelimeleri sağlamaktadır.


## Sonlu Otomatanın Denkliği Örnek
.fx: first

***13061061***

***Ayşe Berika VAROL***
  

## Örnek 1
-       (01 ∪ 0)* düzenli ifadesini NFA formuna dönüştürünüz.

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/1.png)

-       01 durumu:

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/2.png)


##

-       (01 U 0) durumu: 

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/3.png)

-       (01 U 0)* ifademizin sonucu : 

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/4.png)


## Örnek 2

-       (a ∪ b)*ab ∪ c düzenli ifadesini NFA formuna dönüştürünüz.

       L={ ab, aab, bab, aaab, bbbab, abab , c, ...} ifadelerini üretebilir. Yani ifademizi ikiye ayırıp inceleyeceğiz.

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/beri1.png)

	
##

      İfademizin (a ∪ b)*ab kısmı:

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/beri2.png)

	İfademizin (a ∪ b)* kısmı:
![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/beri3.png)
## 

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/beri4.png)

##

(a ∪ b)*ab ∪ c ifademizin sonucu
![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/beri5.png)

-       Soru çözümü sırasında izlenen yöntem parçala fethet yöntemidir.

-       Problem cevabını bildiğimiz basit parçalara bölünmüş ve sonra birleştirilmiştir.

-       Problem en temel 3 durum olan veya (U), üleştirme (concetanation) ve kleene yıldızı 
durumlarını içermektedir.

## Pumping Lemma

.fx: first

***13061040***

***Neşe Ayşen AKGÜN***

## Pumping Lemma (Tulumba Önerisi) 

-      Pumbing Lemma aslında Sonlu Durum makinesidir(FSM).Fakat klasik bir FSM’den biraz farklıdır.Klasik bir FSM şu koşulları sağlar;

     - Durum sayısı sınırlıdır.

     - Geçiş sayısı sınırlıdır.

     - Başlangıç ve bitiş durumları bellidir.

-     Klasik bir FSM kaç tane girdi okuduğunu ve hangi durumlardan geçtiğini saklamaz.Pumbing Lemma ise saklar.

-     Pumbing Lemma  durumları sakladığı için başa dönüp tekrar aynı durumdan geçip geçmediğini anlayabilir.Yani Pumbing Lemma bir dilin düzenli olup olmadığını ispatlamak için kullanılır.

##

-       Pumbing Lemma bilgisayar bilimlerinde dil tasarımı konusunda önemli araçlardan birisidir.Eğer bir dil sonsuz kümeyi kapsıyorsa bu dili ne kadar pompalarsak pompalayalım sonuçta yine aynı dil grubundan olmalıdır. Ve ancak bu sayede bu dilden üretilebilen bütün sonuçların aynı dil grubundan olduğu iddia edilir.

-       Yukarıdaki tanımlamada geçen pompalamak işlemi bir dil gramerinin bir kısmının şişirilmesi, arttırılması veya çoğaltılması olarak algılanabilir.


##

-       L düzenli bir dil ise; L’yi tanıyan bir ya da, kendi aralarında denk birçok sonlu özdevinir vardır.
-       L düzenli dili için;

    - Öncelikle bir “p” sayısı belirlenir.(L’ yi tanıyan özdevinirlerden en küçük duruma sahip olan)
    - Ve bu dil içerisinde p’den daha uzun bir “w” katarı belirlenir.

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/ornek3.png)

***Pumbing işlemi w katarının, p sembolü içinde yapılabilir.***
##
-       İşte böyle bir w katarı aynı zamanda aşağıdaki 4 şartı sağlamalıdır;
    
     - w katarı x,y,z  şeklinde  3 parçaya ayrılabilmelidir.

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/ornek4.png)

-       L dilinde sonsuz katar olduğu için bazı w katarları kendisini tanıyan otomatın durum sayısından daha fazla sembole sahiptir. Bu katarlar için otomat üzerinde döngü oluşur.

     -  x yeniden geçilen ilk duruma kadar olan sembolleri içersin. x eğer boş ise döngü başlangıç durumunuda içine almıştır. 
     -  y katarı, x’ den hemen sonra başlayıp döngünün sonuna kadar olan kısmı içerir. Döngü olduğu için y boş olamaz. 
     -  z katarı döngüden hemen sonra başlayıp w katarının sonuna kadar olan kısmı içersin. z boş ise döngü sonuç durumunuda içine almıştır.

##

-       y’ li kısmı boş olmamalı yani en az 1 tane eleman içermelidir.

    - |y| ≥ 1

-       x ve y teriminin üst değerleri toplamı, toplam üst değerinden küçük veya eşit olmalıdır.
    - |xy| ≤ p

-       Ayrıca dilin düzenli ifade olabilmesi için y teriminin üstü olan i değeri istenildiği kadar arttırılabilmeli ve elde edilen sonuç yine düzenli ifade olmalıdır.

xy^iz ϵ L ve i≥0 olmalıdır.

Örneğin;  i= 4  için w=xy^iz ‘dir. 

Yani xyz, xyyz, xyyyz, xyyyyz  katarların tanır.

------

-      Özet:  Daha basit bir ifadeyle, bir dilden üretilen bir terim üç parçaya bölündüğünde ortasındaki parça boş olmamalı, istenildiği kadar tekrarlanabilmeli ve çıkan bütün sonuçlar yine aynı dilden olmalıdır.
## Pumping Lemma Örnek
.fx: first

***13061068***

***Sinem Aybike HÜR***
##

-       Soru: L={ w |w  eşit sayıda 01 ve 10'lardan oluşuyor} Dilinin düzenli olup olmadığını Pumping Lemma yöntemiyle ispatlayın.

##Cevap

Eşit sayıda 01 ve 10 olmalı

w=x(y^i)z

Durumlar :          x    y    z

                    1    00   1           => 1

                    -    10   -           => 2

                    -    01   -           => 3

                    0    11   0           => 4

-        y^i ' in bütün durumları yukarıda verilmiştir .
xz (11) şeklinde olabilir ve bu durumda 01 ve 10'ların eşitlik durumu sağlanır. 

-        Aynı şekilde 4. durumda da xz (00) şeklinde olup eşitlik sağlanır.
 2.durumda xz ifadesi (01) ve 3. durumda da (10) şeklindedir. 
Sonuç olarak L dilimiz düzenlidir.

##

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/sino1.png)

## Pumping Lemma Örnek
.fx: first

***13061544***

***Hatice GÜNEŞ***

##

-       Soru:  ∑= { a ve b’lerden oluşuyor | palindrom } dili düzenli değildir.

##

-       Palindrom nedir? 

## 
-       Palindrom, tersten ve düzden okunuşu aynı olan cümle,sözcük veya sayılara denir.

-       Palindrom kelimelere örnek verecek olursak:
	
Kek,aba,kazak,radar,süs…

-       Bizim alfabemiz a ve b’lerden oluştuğu için çıktımız:

{ aa, bb, aba, abba, abbba, aabbaa, bab, baab, babab… } şeklindedir.

##

-        Öncelikle dilimizin düzenli olduğunu varsayalım ve tüm çıktılarımızı X, Y, Z olacak şekilde üç parçaya bölelim.

-        S=  xy^iz ⊆ { a^p  b^(p+1)  a^p  }  //  Palindrom ifademizi a^p  b^(p+1)  a^p   şeklinde seçelim.

-        Dilimizi düzenli kabul edip işlemlerimizi ona göre yapacağız. Eğer parçalara ayırıp baktığımız her koşulu sağlıyorsa ifade düzenli olacaktır. Çelişki durumu ile karşılaşırsak bu,dilin düzenli olmadığına işarettir.

-         Kabullerimizi oluştururken y’nin boş olmama durumunu göz önüne alarak x ve z’yi uygun seçmeliyiz.

## x a ve b ‘lerden, y sadece a’lardan oluşsun

</br>

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/sunu1.png)

##y sadece b’lerden, z a ve b’lerden oluşsun

</br>

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/sunu2.png)

## y a ve b’lerden oluşsun
 
</br>

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/sunu3.png)




## SONUÇ

-        Ayırdığımız her parça için baktığımız 3 koşul neticesindeki çelişki durumlarından dolayı bu dilin düzenli olmadığına karar verilmiştir.

##TEŞEKKÜRLER 
.fx: first

--------
Şimdi sıra quizde..


##QUIZ 1.SORU
-        (ab ⋃ aba)* düzenli ifadesini NFA formunda bulunuz.


##QUIZ 2.SORU

-        2) A= {a^ib^j | i>j } dili düzenli değildir, gösteriniz.



##QUIZ 1.SORU CEVABI

L={ε, ab, aba, abab, ababa, aba} ifadelerini üretebilir.

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/quiz1.png)

##QUIZ 2.SORU CEVABI

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/2.1.png)

##

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/2.2.png)

##

![Alt text](/home/sumeyye/bar/duzenli-Ifadeler/resim/2.3.png)




