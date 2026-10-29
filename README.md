# Bushou 214 - Guida Interattiva ai Radicali Cinesi

Una moderna Single Page Web Application (SPA) progettata per l'apprendimento, la consultazione e il ripasso dei **214 radicali (部首 - Bùshǒu)** del cinese mandarino. 

Sviluppata per offrire una leggibilità ottimale sia su desktop sia su dispositivi mobili, con supporto completo a font ad alta risoluzione, Pinyin con toni, caratteri derivati dettagliati, pronuncia audio e quiz interattivo.

[PROVA SUBITO LA WEBAPP](https://sites.google.com/view/basilinguacinese/) 
---

## 🌟 Caratteristiche Principali

- **Dataset Completo (214 Radicali):** Tutti i 214 radicali tradizionali Kangxi numerati in sequenza canonica, completi di:
  - Carattere in grande stile calligrafico cinese (`Noto Serif SC`).
  - Trascrizione fonetica **Pinyin con accenti tonali**.
  - Traduzione e significato in lingua italiana.
  - Numero esatto di tratti.
  - Note etimologiche e mnemoniche.
- **Caratteri Derivati con Dettagli e Audio:**
  - Ogni radicale mostra esempi concreti di ideogrammi composti derivati.
  - Ciascun esempio include **carattere grande**, **Pinyin** e **traduzione in italiano**.
  - **Pronuncia vocale nativa (Web Speech API):** tocca qualsiasi carattere derivato o radicale per ascoltarne la corretta pronuncia in mandarino (`zh-CN`).
- **Filtri e Ricerca in Tempo Reale:**
  - Ricerca istantanea per carattere, Pinyin, significato italiano o numero identificativo.
  - Filtro rapido per **numero di tratti** (da 1 a 17 tratti) e per **categoria**.
- **Tema Scuro Nativo (Dark Mode):**
  - Configurato di default con una palette ad alto contrasto (`slate-950` / `red-500` / `amber-400`).
  - Toggle rapido chiaro/scuro con salvataggio delle preferenze nel `localStorage`.
- **Sistema Preferiti:**
  - Possibilità di contrassegnare i radicali più complessi con una stella.
  - Scheda dedicata "Salvati" per sessioni di ripasso mirate e veloci.
- **Modalità Quiz:**
  - Test a scelta multipla generato casualmente sul pool dei 214 radicali.
  - Feedback visivo immediato su risposte esatte o errate e calcolo del punteggio finale.
- **Zero Dipendenze di Build (Single-File Mandate):**
  - Funziona direttamente aprendo il file `.html` in qualsiasi browser moderno, senza necessità di Node.js, Webpack, Bundler o server di backend.

---

## 📱 Ottimizzazione Mobile & Tipografia

- Font ingranditi per evitare l'affaticamento visivo:
  - Caratteri cinesi renderizzati con font serif ad alta definizione.
  - Pinyin con toni chiaramente leggibili anche su schermi di piccole dimensioni.
  - Schede responsive con layout a griglia adattiva (da 2 a 8 colonne a seconda del display).

---

## 🚀 Come Eseguire il Progetto

Non è richiesta alcuna installazione:

1. **Clona la repository:**

   ```bash
   git clone https://github.com/labinfo-projects/bushou-214.git
   cd bushou-214
   ```

2. **Apri il file:**
   Fai doppio clic su `radicali_cinesi.html` oppure aprilo tramite terminale:

   ```bash
   # Su macOS
   open radicali_cinesi.html
   
   # Su Linux
   xdg-open radicali_cinesi.html
   
   # Su Windows
   start radicali_cinesi.html
   ```

3. *(Opzionale)* Avvia un web server locale rapido:

   ```bash
   python3 -m http.server 8080
   # Apri http://localhost:8080 nel tuo browser
   ```

---

## 🌐

---

## 🛠️ Tecnologie Utilizzate

- **HTML5 & Vanilla JavaScript (ES6+):** Logica applicativa, gestione dello stato (quiz, filtri, local storage).
- **Tailwind CSS (CDN):** Styling reattivo e gestione delle palette chiaro/scuro.
- **Web Speech API:** Sintesi vocale per la pronuncia in lingua cinese mandarino.
- **FontAwesome 6:** Iconografia dell'interfaccia utente.
- **Google Fonts:**
  - *Inter* per testi e interfaccia.
  - *Noto Serif SC* per una resa calligrafica accurata e tradizionale dei caratteri cinesi.

---

## 📄 Licenza

Questo progetto è distribuito sotto licenza [MIT](https://github.com/labinfo-projects/bushou-214/blob/main/LICENSE). Sentiti libero di utilizzarlo, modificarlo e distribuirlo per scopi personali o didattici.
