## PHP-to-Excel

EzSQL kullanarak, basit bir şekilde veritabanından gelen verileri Excel'e aktaran fonksiyon

Stackoverflow'da bulduğum fonksiyon, hepimizin işine yarayacaktır.
Fonksiyon'a bir kaç parametre göndermemiz gerekiyor.
### DosyaAdi : Excel dosyasının adı
### $columns : Sütun Başıkları, array olarak
### $data: Kolon verileri
### $replaceDotCol: Decimal kolonlardaki noktayı (.) virgüle (,) dönüştürüelecek kolon numarası belirtilmelidir.
### Örneğin; Kolon 4'ün verilerinde nokta değilde virgül görülmesini istiyorsanız ilgili kolonun array key numarasını belirtmelisiniz. 
### İlk kolonun key numarası 0'dır.
 
# exportExcel('DosyaAdi',$columns,$data,$replaceDotCol);
