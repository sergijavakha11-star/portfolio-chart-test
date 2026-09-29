# პორტფელის ჩარტი — ტესტის ვერსია

ერთი სტატიკური გვერდი (`index.html`), build-ის და დამოკიდებულებების გარეშე. ციფრები საცდელია.
Figma: `fGbqU0w597OlqwahjQSj6M`, სექცია `18609:46674` (ეკრანები 01–06).

## Vercel-ზე გამოქვეყნება

1. github.com → **New repository** → სახელი, მაგ. `portfolio-chart-test` (Private-იც მუშაობს) → **Create repository**.
2. ცარიელ repo-ში → **uploading an existing file** → ჩააგდე `index.html` და `README.md` → **Commit changes**.
3. vercel.com → **Add New → Project** → ამ repo-ს გასწვრივ **Import** → Framework Preset: **Other** → **Deploy**.
4. ლინკი: `https://portfolio-chart-test.vercel.app` (ან Vercel-ის მიერ მიცემული სახელი).

## განახლება

GitHub-ზე `index.html`-ს ახალ ვერსიას ატვირთავ (Add file → Upload files → Commit) — Vercel თვითონ გადააწყობს 1 წუთში, ლინკი იგივე რჩება.

## ლოკალურად

```
cd ~/Desktop/portfolio-chart-web && python3 -m http.server 8080 --bind 0.0.0.0
```
