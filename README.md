# Mój Dziennik – Stan Psychiczny 📓

Aplikacja PWA do monitorowania stanu psychicznego i emocji, jako wsparcie psychoterapii.

---

## 🚀 Jak wdrożyć na telefon (krok po kroku)

### Krok 1 — Załóż konto GitHub (jeśli nie masz)
Wejdź na https://github.com i zarejestruj się (darmowe).

### Krok 2 — Wgraj projekt na GitHub
1. Kliknij **"New repository"** (zielony przycisk)
2. Nazwa: `mental-monitor`, zostaw publiczne, kliknij **Create**
3. Na stronie nowego repo kliknij **"uploading an existing file"**
4. Przeciągnij i upuść **wszystkie pliki i foldery** z tego archiwum ZIP
   - ⚠️ Ważne: upewnij się że wgrałeś też folder `src/` i `public/`
5. Kliknij **"Commit changes"**

### Krok 3 — Załóż konto Vercel i wdróż
1. Wejdź na https://vercel.com
2. Kliknij **"Sign Up"** → **"Continue with GitHub"** (połącz z GitHub)
3. Kliknij **"Add New Project"**
4. Znajdź `mental-monitor` na liście → kliknij **"Import"**
5. Nic nie zmieniaj, kliknij **"Deploy"**
6. Po ~1 minucie dostaniesz link np. `mental-monitor-abc.vercel.app` ✅

### Krok 4 — Zainstaluj na telefonie jako aplikację

**Na iPhone (Safari):**
1. Otwórz link w Safari (nie Chrome!)
2. Kliknij ikonę **Udostępnij** (kwadrat ze strzałką w górę)
3. Wybierz **"Dodaj do ekranu głównego"**
4. Kliknij **"Dodaj"** → gotowe!

**Na Androidzie (Chrome):**
1. Otwórz link w Chrome
2. Pojawi się baner **"Dodaj do ekranu głównego"** — kliknij
3. Lub: menu ⋮ → **"Dodaj do ekranu głównego"**

---

## 💻 Uruchamianie lokalnie (opcjonalne)

Potrzebujesz Node.js (https://nodejs.org)

```bash
npm install
npm run dev
```

Aplikacja otworzy się na http://localhost:5173

---

## 🔒 Prywatność

Wszystkie dane są przechowywane **wyłącznie na Twoim urządzeniu** (localStorage).
Nic nie jest wysyłane do żadnego serwera.

---

## 📁 Struktura projektu

```
mental-monitor/
├── src/
│   ├── main.jsx        # punkt wejścia React
│   └── App.jsx         # cała aplikacja
├── public/
│   ├── icon-192.png
│   ├── icon-512.png
│   └── apple-touch-icon.png
├── index.html
├── vite.config.js      # konfiguracja Vite + PWA
└── package.json
```
