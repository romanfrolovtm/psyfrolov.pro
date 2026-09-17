# Статья №5 (PL) — terapia ekspozycyjna

Файл: `blog-terapia-ekspozycyjna.html` · Запрос «terapia ekspozycyjna» — в показах. Эта статья уже объёмная (~1300 слов), тело почти не трогаем — оптимизируем `<title>`/`<meta>`, расширяем FAQ, добавляем 2 блока глубины (hierarchia + skala SUDS) и JSON-LD.

---

## 1. TITLE и META

**`<title>`**
```
Terapia ekspozycyjna — na czym polega i jak działa (CBT)
```

**`<meta name="description">`**
```
Terapia ekspozycyjna w CBT: dlaczego unikanie nasila lęk, na czym polega hierarchia ekspozycji i skala SUDS, dowody naukowe i bezpieczeństwo metody przy lęku, fobiach i PTSD.
```

---

## 2. ДВА НОВЫХ БЛОКА В ТЕЛО (вставить перед «Kroki praktyczne»)

Тело статьи хорошее — оставляем. Добавляем два раздела с конкретикой (уникальный контент + под запросы «hierarchia», «skala lęku»):

```html
<h2>Hierarchia ekspozycji — przykład</h2>
<p>Podstawą metody jest lista sytuacji uszeregowanych od najłatwiejszej do najtrudniejszej. Zaczyna się od pozycji ocenianych nisko, nie od najtrudniejszej. Przykładowa hierarchia przy lęku przed wystąpieniami:</p>
<ul>
  <li>Nagranie krótkiej wypowiedzi tylko dla siebie.</li>
  <li>Wypowiedź przy jednej zaufanej osobie.</li>
  <li>Zabranie głosu w małej grupie.</li>
  <li>Krótka prezentacja przed zespołem.</li>
  <li>Wystąpienie przed większą publicznością.</li>
</ul>
<p>Do kolejnego kroku przechodzi się dopiero wtedy, gdy lęk na poprzednim wyraźnie spada.</p>

<h2>Skala SUDS — jak mierzyć lęk</h2>
<p>W praktyce używa się prostej skali <strong>SUDS</strong> (Subjective Units of Distress) od 0 do 100, gdzie 0 to całkowity spokój, a 100 — najsilniejszy wyobrażalny lęk. Ekspozycję zwykle zaczyna się od sytuacji ocenianych na 30–40, a nie od najtrudniejszych. Podczas ćwiczenia obserwuje się, jak poziom SUDS samoistnie opada — to właśnie doświadczenie „lęk mija sam” jest istotą metody.</p>
```

---

## 3. FAQ (расширить)

```html
<h2>Najczęściej zadawane pytania</h2>

<h3>Na czym polega terapia ekspozycyjna?</h3>
<p>Na stopniowym, kontrolowanym kontakcie z sytuacją wywołującą lęk — pod okiem terapeuty — tak długo, aż lęk samoistnie opadnie. Dzięki temu mózg uczy się, że sytuacja jest bezpieczna, a unikanie przestaje być potrzebne.</p>

<h3>Czy to nie jest zbyt stresujące?</h3>
<p>Tempo, intensywność i czas są ustalane wcześniej i pozostają pod kontrolą klienta. Zaczyna się od łatwiejszych pozycji hierarchii, dlatego przy prawidłowym prowadzeniu metoda jest bezpieczna.</p>

<h3>Czy mogę ćwiczyć ekspozycję samodzielnie?</h3>
<p>Przy łagodnych, konkretnych lękach — czasem tak. Przy zaburzeniach lękowych, napadach paniki i traumie prowadzenie terapeuty jest istotne dla skuteczności i bezpieczeństwa.</p>

<h3>Czy lęk wróci po zakończeniu?</h3>
<p>Łagodny lęk może wracać w okresach stresu, ale nabyte umiejętności zwykle pozwalają szybciej sobie z nim poradzić.</p>
```

---

## 4. JSON-LD

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "Terapia ekspozycyjna: praca z lękami i niepokojem",
  "inLanguage": "pl",
  "author": { "@id": "https://psyfrolov.pro/#roman" },
  "publisher": { "@id": "https://psyfrolov.pro/#roman" },
  "mainEntityOfPage": "https://psyfrolov.pro/blog-terapia-ekspozycyjna.html",
  "datePublished": "2026-06-01",
  "dateModified": "2026-09-17",
  "about": ["terapia ekspozycyjna", "zaburzenia lękowe", "CBT", "fobie"],
  "description": "Terapia ekspozycyjna w CBT: hierarchia ekspozycji, skala SUDS, dowody naukowe i bezpieczeństwo metody."
}
</script>
```

---

## 5. Внутренние ссылки
- С `blog-pl.html`, `blog.html`.
- С `pl.html` / `method.html` — «terapia ekspozycyjna» → ссылка.
- Взаимные ссылки со смежными PL-статьями: `blog-restrukturyzacja-poznawcza.html`, `blog-wypalenie-emocjonalne.html`.
