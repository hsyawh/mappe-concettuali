# 🗺️ Mappe Concettuali · Novak Web App

Applicazione web autonoma, leggera e interamente contenuta in un singolo file HTML (Single File Web App), sviluppata per la creazione, modifica ed esportazione di mappe concettuali secondo la metodologia di **Joseph Novak**.

---

## ✨ Caratteristiche Principali

- **Canvas Interattivo Autonomo**: 
  - Doppio clic per creare un nuovo concetto o modificare il testo.
  - Trascina il pallino (`●`) sotto un concetto per creare un collegamento con un altro nodo.
  - Zoom con rotella del mouse e panoramica trascinando lo sfondo.
- **Importazione Rapida da Testo / Markdown**:
  - Incolla un riassunto o un elenco puntato indentato per generare automaticamente una mappa completa di nodi e relazioni.
- **Stili e Forme Personalizzabili**:
  - **Forme dei nodi**: Rettangolo arrotondato, Rettangolo, Ellisse/Ovale (per gli esempi) e Capsula.
  - **Stili di linea**: Curva morbida, Linea retta, Ortogonale (a scalino).
  - **Colori**: Palette predefinite e supporto al tema Chiaro/Scuro (Light/Dark Mode).
- **Proposizioni e Validazione**:
  - Scheda dedicata con verifica in tempo reale delle frasi create (*Concetto + Parola di legame + Concetto*).
  - Evidenziazione dei collegamenti privi di etichetta o dei concetti isolati.
- **Esportazione Multi-Formato**:
  - **Copia negli Appunti**: Copia l'immagine della mappa direttamente negli appunti di sistema per incollarla al volo su Word, PowerPoint o Docs.
  - **Formato JSON**: Salva la mappa sul computer per poterla riaprire e modificare in seguito.
  - **PNG / SVG**: Esporta in alta risoluzione o in vettoriale nitido.
  - **Stampa / PDF**: Layout ottimizzato per la stampa orizzontale.
- **Strumenti di Produttività**:
  - Layout automatico gerarchico (dall'alto verso il basso).
  - Griglia magnetica (*Snap-to-Grid*).
  - Ricerca ed evidenziazione dei concetti in tempo reale.
  - Annulla/Ripristino azioni (<kbd>Ctrl</kbd> + <kbd>Z</kbd> / <kbd>Ctrl</kbd> + <kbd>Y</kbd>).

---

## 🚀 Come Usarla

L'applicazione è autonoma e non richiede installazione, server o librerie esterne.

### Opzione 1: Online (GitHub Pages)
Apri l'applicazione direttamente dal tuo browser tramite il link di GitHub Pages:
`https://<tuo-utente>.github.io/<nome-repository>/`

### Opzione 2: In Locale sul PC
1. Scarica o salva il file `index.html`.
2. Fai doppio clic sul file `index.html` per aprirlo e usarlo in qualsiasi browser web.

---

## ⌨️ Scorciatoie da Tastiera

| Scorciatoia | Azione |
| :--- | :--- |
| **Doppio clic sul vuoto** | Crea un nuovo concetto al punto |
| **Doppio clic su nodo/legame** | Modifica il testo inline |
| <kbd>Tab</kbd> *(con nodo selezionato)* | Crea ed etichetta un concetto figlio |
| <kbd>N</kbd> | Crea un nuovo concetto al centro dello schermo |
| <kbd>Ctrl</kbd> + <kbd>D</kbd> | Duplica il concetto selezionato |
| <kbd>Canc</kbd> / <kbd>Backspace</kbd> | Elimina elemento selezionato |
| <kbd>Ctrl</kbd> + <kbd>Z</kbd> | Annulla azione |
| <kbd>Ctrl</kbd> + <kbd>Y</kbd> | Ripristina azione |
| <kbd>Ctrl</kbd> + <kbd>0</kbd> | Centra e inquadra l'intera mappa |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> | Salva la mappa in formato `.json` |
| **Frecce Direzionali** | Sposta il concetto selezionato |

---

## 📥 Formato di Importazione Testo

Puoi generare mappe istantaneamente usando il pulsante **Importa** ed incollando testo strutturato come questo:

```text
Energia
  - produce: Lavoro
  - si divide in: Energia Cinetica
  - si divide in: Energia Potenziale
    - dipende da: Altezza
