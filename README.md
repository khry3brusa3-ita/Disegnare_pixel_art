# Disegnare_pixel_art
html css js per creare pixel art e spritesheet

# 🎨 Unity Pixel Art Creator - Suite Grafica & Animazioni

Benvenuto nel repository di **Unity Pixel Art Creator**, un'applicazione web interattiva, leggera e potente creata per disegnare pixel art, creare sprite 2D e gestire animazioni ed esportazioni per videogiochi direttamente dal tuo browser! Il progetto è interamente racchiuso in un unico file combinato (HTML, CSS e JavaScript), facilitando la massima portabilità senza necessità di installazioni complesse.

---
🖱️ Clicca e trascina il mouse sulla griglia per disegnare i tuoi pixel e animare i tuoi sprite!

## 🚀 Funzionalità Principali (Spiegate Semplici)

### ✏️ 1. Strumenti di Disegno e Tavolozza
* **Matita Pixel:** Disegna a mano libera sulla griglia posizionando pixel singoli con estrema precisione.
* **Tavolozza Colori Avanzata (🎨):** Seleziona qualsiasi sfumatura o tonalità di colore grazie al selettore cromatico nativo integrato.
* **Memoria Colori Recenti:** Memorizza automaticamente fino a 12 colori utilizzati di recente nella barra superiore, consentendoti di richiamarli istantaneamente con un semplice clic.
* **Gomma (🧼):** Cancella i singoli pixel ripristinando la trasparenza dello sfondo.
* **Pulisci Frame (🧹):** Svuota completamente il disegno del frame selezionato lasciando la griglia pulita.

### 📐 2. Canvas, Griglia e Precisione
* **Risoluzione Modificabile:** Scegli al volo tra i formati standard per pixel art (**16x16**, **24x24**, **32x32**, **48x48**) oppure imposta dimensioni **Custom** (personalizzabili in larghezza e altezza).
* **Zoom Dinamico:** Modifica in tempo reale la dimensione visiva dei pixel tramite lo slider dedicato per lavorare comodamente sui dettagli.
* **Annulla / Ripristina (↩️ / ↪️):** Mantiene una cronologia fino a 30 passaggi. Se commetti un errore, puoi tornare indietro o ripristinare i tratti precedenti in un attimo.

### 🎬 3. Gestione Animazioni e Frame
* **Aggiungi Frame (+ Nuovo):** Crea un nuovo frame vuoto mantenendo la stessa risoluzione per continuare la tua sequenza d'animazione.
* **Duplica Frame (📑):** Copia esattamente il frame corrente in un nuovo fotogramma, ideale per realizzare animazioni fluide attraverso piccole modifiche progressive.
* **Anteprime in Tempo Reale:** La barra laterale mostra miniature in scala di ciascun frame con numerazione e sfondo a scacchiera per visualizzare la trasparenza.
* **Eliminazione Rapida:** Rimuovi i singoli frame non più necessari direttamente dalla barra laterale.

### 💾 4. Esportazione Pronta per Game Engine
* **Salva Frame Singolo (🖼️):** Scarica l'immagine PNG trasparente del singolo fotogramma attivo alla sua risoluzione nativa.
* **Esporta Spritesheet (🎬):** Combina automaticamente tutti i frame dell'animazione in un'unica striscia orizzontale PNG (*Spritesheet*), pronta per essere usata nei game engine.

---

## 💻 Come Usare l'Applicazione

1. **Apertura:** Scarica il file `pixel_art_per_videogiochi.html` sul tuo computer.
2. **Nessuna Configurazione:** Fai doppio clic sul file per aprirlo in un qualsiasi browser web moderno (Chrome, Edge, Firefox, Safari).
3. **Uso Offline:** L'intera app funziona al 100% offline senza necessità di server o connessione ad internet.

---

## 🎮 Importazione Diretta in Unity

Per utilizzare lo spritesheet generato all'interno di **Unity**:

1. Trascina il file PNG scaricato direttamente nella cartella `Assets` del tuo progetto.
2. Seleziona l'immagine e imposta i parametri nell'**Inspector**:
   * **Texture Type:** `Sprite (2D and UI)`
   * **Sprite Mode:** `Multiple`
   * **Filter Mode:** `Point (no filter)` *(Fondamentale per mantenere i pixel perfettamente nitidi)*
   * **Compression:** `None`
3. Clicca su **Apply**, poi apri lo **Sprite Editor** ed esegui lo *Slice* (**Grid By Cell Size**) inserendo le dimensioni utilizzate nel canvas (es. 16x16 o 32x32).

Progetto sviluppato per coniugare l'immediatezza della pixel art con la velocità di creazione di assets per videogiochi 2D! 🎨👾✨






# 🎨 Unity Pixel Art Creator - Graphics & Animation Suite

Welcome to the repository for **Unity Pixel Art Creator**, an interactive, lightweight, and powerful web application designed to draw pixel art, create 2D sprites, and manage game animations and exports directly from your browser! The project is completely self-contained in a single combined file (HTML, CSS, and JavaScript), making it highly portable with no complex installation required.

---
🖱️ Click and drag your mouse on the grid to draw your pixels and animate your sprites!

## 🚀 Key Features (Explained Simply)

### ✏️ 1. Drawing Tools & Palette
* **Pixel Pencil:** Draw freehand on the grid placing single pixels with extreme precision.
* **Advanced Color Palette (🎨):** Select any shade or hue thanks to the built-in native color picker.
* **Recent Colors Memory:** Automatically stores up to 12 recently used colors in the top bar, allowing you to instantly recall them with a single click.
* **Eraser (🧼):** Erase individual pixels, restoring background transparency.
* **Clear Frame (🧹):** Completely clear the drawing on the selected frame, leaving a clean grid.

### 📐 2. Canvas, Grid & Precision
* **Adjustable Resolution:** Choose on the fly between standard pixel art formats (**16x16**, **24x24**, **32x32**, **48x48**) or set **Custom** dimensions (customizable width and height).
* **Dynamic Zoom:** Adjust the visual pixel size in real time using the dedicated slider to comfortably work on fine details.
* **Undo / Redo (↩️ / ↪️):** Maintains a history of up to 30 steps. If you make a mistake, you can go back or restore previous strokes in an instant.

### 🎬 3. Animation & Frame Management
* **Add Frame (+ New):** Create a new blank frame while keeping the same resolution to continue your animation sequence.
* **Duplicate Frame (📑):** Copy the exact current frame into a new frame, ideal for creating smooth animations through small progressive tweaks.
* **Real-time Previews:** The sidebar displays scaled thumbnails of each frame with numbering and a checkerboard background to visualize transparency.
* **Quick Deletion:** Remove individual frames you no longer need directly from the sidebar.

### 💾 4. Game Engine Ready Export
* **Save Single Frame (🖼️):** Download the transparent PNG image of the active single frame at its native resolution.
* **Export Spritesheet (🎬):** Automatically combine all animation frames into a single horizontal PNG strip (*Spritesheet*), ready to be used in game engines.

---

## 💻 How to Use the Application

1. **Opening:** Download the `pixel_art_per_videogiochi.html` file to your computer.
2. **Zero Configuration:** Double-click the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. **Offline Use:** The entire app works 100% offline with no need for a server or internet connection.

---

## 🎮 Direct Import into Unity

To use the generated spritesheet inside **Unity**:

1. Drag the downloaded PNG file directly into your project's `Assets` folder.
2. Select the image and configure the parameters in the **Inspector**:
   * **Texture Type:** `Sprite (2D and UI)`
   * **Sprite Mode:** `Multiple`
   * **Filter Mode:** `Point (no filter)` *(Essential for keeping pixels perfectly sharp)*
   * **Compression:** `None`
3. Click **Apply**, then open the **Sprite Editor** and perform a *Slice* (**Grid By Cell Size**), entering the dimensions used on the canvas (e.g., 16x16 or 32x32).

Project developed to combine the immediacy of pixel art with the speed of creating 2D game assets! 🎨👾✨

