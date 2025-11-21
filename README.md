# 💎 Prisma Code Editor

<img width="165" height="37" alt="Screenshot 2025-11-21 233351" src="https://github.com/user-attachments/assets/828ffd4a-7eec-4607-b3a7-ba73551fb170" />


> **Prisma Code Editor** è un editor di codice web frontend leggero, progettato per offrire un'esperienza di sviluppo immediata con evidenziazione della sintassi, formattazione automatica e anteprima live, il tutto senza dipendenze da API esterne.

Realizzato con **React**, **TypeScript** e **Vite**, Prisma offre un ambiente sandbox sicuro e veloce per prototipare idee in HTML, CSS e JavaScript.

---

## ✨ Funzionalità Principali

### 👨‍💻 Esperienza di Editing
* **Multi-Tab Editor:** Scrivi separatamente HTML, CSS e JavaScript con tab dedicati.
* **Syntax Highlighting:** Evidenziazione del codice chiara e leggibile grazie a PrismJS (tema Tomorrow).
* **Formattazione Automatica:** Riordina il tuo codice istantaneamente con il pulsante dedicato o scorciatoie da tastiera.
* **Smart Editing:** Chiusura automatica di tag e parentesi, indentazione e gestione dei commenti.

### 🚀 Produttività & UI
* **Live Preview:** Anteprima in tempo reale del risultato mentre scrivi.
* **Modalità Fullscreen:** Espandi l'anteprima a schermo intero per testare la responsività.
* **Cronologia (Undo/Redo):** Sistema di cronologia robusto per annullare o ripristinare le modifiche senza paura.
* **Persistenza Locale:** Le tue impostazioni e il codice vengono salvati automaticamente nel `localStorage` del browser.

### 📦 Export & Condivisione
* **Esporta Progetto:** Scarica il tuo lavoro come un singolo file `.html` pronto per essere eseguito ovunque, contenente tutto il tuo codice (HTML+CSS+JS).

---

## 🛠️ Tecnologie Utilizzate

Il progetto è costruito utilizzando uno stack moderno e performante:

*  **React 19** - Libreria UI.
*  **TypeScript** - Tipizzazione statica per robustezza.
*  **Vite** - Build tool di nuova generazione.
*  **Tailwind CSS** - Utility-first CSS framework (via CDN).
* **Lucide React** - Icone vettoriali moderne.
* **PrismJS** - Tokenizer per l'evidenziazione della sintassi.

---

## 🚀 Installazione e Avvio Locale

Per eseguire il progetto sul tuo computer:

1.  **Clona il repository:**
    ```bash
    git clone [https://github.com/tuo-username/prisma-code-editor.git](https://github.com/tuo-username/prisma-code-editor.git)
    cd prisma-code-editor
    ```

2.  **Installa le dipendenze:**
    ```bash
    npm install
    ```
    **

3.  **Avvia il server di sviluppo:**
    ```bash
    npm run dev
    ```
    Il sito sarà disponibile su `http://localhost:3000`.

4.  **Build per produzione:**
    Per creare la versione ottimizzata (cartella `dist`):
    ```bash
    npm run build
    ```
    **

---

## ⌨️ Scorciatoie da Tastiera

| Azione | Shortcut (Default) |
| :--- | :--- |
| **Formatta Codice** | `Ctrl + Enter` |
| **Commenta Riga** | `Ctrl + /` |
| **Annulla (Undo)** | `Ctrl + Z` |
| **Ripeti (Redo)** | `Ctrl + Y` o `Ctrl + Shift + Z` |

> *Nota: Le scorciatoie possono essere personalizzate nelle impostazioni dell'editor.*

---

## 📄 Licenza

Distribuito sotto licenza MIT. Vedere `LICENSE` per maggiori informazioni.

---

<div align="center">
  <sub>Realizzato con ❤️ usando React e Vite</sub>
</div>
