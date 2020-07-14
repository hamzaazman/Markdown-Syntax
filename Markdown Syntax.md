# Markdown Syntax

> **Markdown**, düz-metin-biçimlendirme sözdizimine sahip bir hafif işaretleme dili. Tasarımı, birçok çıktı biçimine dönüştürülmesine izin verir, ancak aynı ada sahip orijinal araç yalnızca HTML'yi destekler. Markdown genellikle benioku dosyalarını biçimlendirmek, çevrimiçi tartışma forumlarına mesaj yazmak ve düz metin düzenleyicisi kullanarak zengin metin oluşturmak için kullanılır.

## Heading / Başlık

| Markdown                | HTML                         |
| ----------------------- | ---------------------------- |
| \# Heading level 1      | `<h1> Heading level 1 </h1>` |
| \## Heading level 2     | `<h2> Heading level 2 </h2>` |
| \### Heading level 3    | `<h3> Heading level 3 </h3>` |
| \#### Heading level 4   | `<h4> Heading level 4 </h4>` |
| \##### Heading level 5  | `<h5> Heading level 5 </h5>` |
| \###### Heading level 6 | `<h6> Heading level 6 </h6>` |

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6



## Paragraph / Paragraf

Paragraf oluşturmak için herhangi bir boş satırı kullanabilirsiniz. Ekstra bir tag kullanmaya gerek yok.

*Markdown*

---

Lorem ipsum dolor sit amet, consectetur adipiscing elit

Lorem ipsum dolor sit amet, consectetur adipiscing elit

*HTML*

---

`<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>`

`<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>`



## Emphasi / Vurgu

**Bold**

Metni kalın yapmak için başına ve sonuna iki `*` (yıldız) veya `_`iki (altçizgi) ekleyebilirsiniz. Ancak aralarında boşluk olmasın.

| Markdown                              | Çıktı                               |
| ------------------------------------- | ----------------------------------- |
| `**Lorem** ipsum dolor __sit__ amet.` | **Lorem** ipsum dolor __sit__ amet. |



**Italic**

Metni kalın yaparken 2 adet yıldız ve altçizgi kullanmıştık. Burda ise 1 adet kullanıyoruz. Gene aralarında boşluk bırakılmadığına dikkat edelim.

| Markdown                          | Çıktı                           |
| --------------------------------- | ------------------------------- |
| `*Lorem* ipsum dolor _sit_ amet.` | *Lorem* ipsum dolor _sit_ amet. |



**Bold & Italic**

Pekala her ikisini nasıl kullanabiliriz. Yani hem kalın hem italic olacak.

| Markdown             | Çıktı             |
| -------------------- | ----------------- |
| `***Lorem*** ipsum` | ***Lorem*** ipsum |
| `___Lorem___ ipsum`  | ___Lorem___ ipsum |
| `__*Lorem*__ ipsum`  | __*Lorem*__ ipsum |
| `**_Lorem_** ipsum`  | **_Lorem_** ipsum |

> Tek yıldız veya tek altçizgi kullanırsak **italic**, çift olarak kullanırsak **bold**, 3 adet kullanırsak **hem bold hem italic** yapıyor. Farklı farklı şekilde kullanabilirsiniz.



## Blockquote / Alıntı

Alıntı yapmak için ise `>` işareti kullanılır.

`> Lorem ipsum dolor sit amet.`

> Lorem ipsum dolor sit amet.



## List / Liste

Listeler, **sıralı (ordered)** ve  **sırasız (unordered)** olarak ikiye ayrılıyor.

**Sıralı Listeler/ Ordered Lists**

Direk 1. (nokta) boşluk yaptığınızda liste oluşuyor. Entere bastığınızda sırayla gittiğini göreceksiniz.

*Markdown*

1. First item
2. Second item
   1. Lorem İpsum
   2. Lorem İpsum
   3. Lorem İpsum
3. Third item

> Tab tuşuna basarak iç içe liste oluşturabilirsiniz. 



```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    	<ol>
        	<li>Lorem İpsum</li>
        	<li>Lorem İpsum</li>
        	<li>Lorem İpsum</li>
    	</ol>
    <li>Third item</li>
</ol>
```

**Sırasız Listeler / Unordered Lists**

Sırasız listelerde de direk listenin önüne tire (-), yıldız (*), veya artı (+) işareti ekleyin

*Markdown*

```markdown
- First item
- Second item 
- Third item
```

- First item
- Secon item
  - lorem ipsum
  - lorem ipsum
- Third item
