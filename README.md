# En Ucuz Sepet Karşılaştırması 🛒

Bu proje, C# dili kullanılarak **Şok Market** ve **CarrefourSA** online mağazalarından belirtilen ürünlerin fiyatlarını çekmek (**Web Scraping**) ve kullanıcının sepetindeki ürünlerin toplam maliyetini en ucuza hangi marketten karşılayabileceğini göstermek amacıyla geliştirilmiştir.

## ✨ Özellikler

* **Çoklu Market Desteği:** Şok Market ve CarrefourSA web sitelerinden eş zamanlı veri çeker.
* **Asenkron İşlem:** `HttpClient` ve `Task.WhenAll` yapısı ile birden fazla ürünü ve marketi aynı anda hızlı bir şekilde sorgular.
* **Ürün Eşleştirme:** Girilen ürün adıyla market sitelerindeki ürün başlıklarını kelime bazında karşılaştırarak en uygun ürünleri bulur.
* **Fiyat Karşılaştırması:** Her bir ürün için en ucuz fiyatı belirler ve sepetin **toplam** en ucuz maliyetini hesaplar.
* **Kullanım Kolaylığı:** Kullanıcıdan ürün adlarını virgülle ayrılmış bir liste olarak alır.

---

## 2. 🚀 Kurulum ve Çalıştırma

Bu projeyi çalıştırmak için **.NET Runtime**'ın kurulu olması gerekmektedir.

### Klonlama
Projeyi yerel makinenize klonlayın:

```bash
git clone <PROJE_REPO_ADRESİ>
cd EnUcuzSepet
