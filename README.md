# AnimationCards
![](AnimationCards.gif)

**Dinamik Panellerle Etkileşimli Bir Web Sayfası**

Bu JavaScript dosyası, kullanıcıların tıkladıkları paneli vurgulayan basit bir etkileşimli web sayfasını yönetir. İlgili JavaScript projesi için sade ve açıklayıcı bir açıklama şu şekilde olabilir:

**JavaScript Proje Açıklaması:**

Bu proje, kullanıcıların bir dizi panel arasında geçiş yapmasına olanak tanıyan bir web sayfasını oluşturur. Her bir panel, tıklandığında aktif hale gelir ve diğer panellerdeki aktif durumu kaldırır.

- **JavaScript Kodu:**
  - `panels` değişkeni: HTML'de sınıfı "panel" olan tüm öğeleri seçer.
  - `panels.forEach` döngüsü: Her bir panel öğesine tıklanma olayını dinler.
  - `removeActive` fonksiyonu: Aktif durumu kaldırmak için tüm panellerin üzerinde döner.

- **HTML Yapısı:**
  - Panelleri içeren bir ana bölme (`<div class="panels">`).
  - Her bir paneli temsil eden öğeler (`<div class="panel">`).

- **CSS Stili:**
  - Panel öğeleri için stil kuralları, özellikle tıklanan panelin görünümünü vurgulamak için.

- **Kullanılan Teknolojiler:**
  - Temel HTML ve CSS.
  - JavaScript etkileşimi sağlamak için.

Projeyi kullanmak için:
1. Web sayfasını tarayıcıda açın.
2. Panellerden birine tıklayın.
3. Tıkladığınız panel aktif hale gelir ve diğer panellerdeki aktif durumu kaldırır.

Bu proje, paneller arasında geçiş yapmak isteyen kullanıcılar için basit ve etkileşimli bir web sayfası sunar. Panelleri genişletebilir ve geliştirebilirsiniz.
