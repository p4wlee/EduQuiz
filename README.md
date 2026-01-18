# 🎓 EduQuiz

EduQuiz è una mini piattaforma di quiz online sviluppata come progetto didattico per esercitarsi con **Node.js**, **Express** e **JavaScript**.  
L’obiettivo del progetto è mostrare come realizzare una semplice **API REST** e collegarla a un **frontend vanilla JS**, gestendo domande, risposte e punteggio.

Il progetto segue un approccio pratico: **backend + frontend** comunicano tramite chiamate HTTP (`fetch`).

---

## 🚀 Funzionalità principali

- Avvio del quiz con reset del punteggio
- Recupero delle domande dal server
- Risposte a scelta multipla
- Verifica della correttezza delle risposte
- Calcolo del punteggio lato server
- Visualizzazione del risultato finale
- Possibilità di ricominciare il quiz

---

## 🧠 Tecnologie utilizzate

### Backend
- **Node.js**
- **Express**
- API REST
- Dati salvati in memoria (array di oggetti)

### Frontend
- **HTML**
- **CSS**
- **JavaScript Vanilla**
- `fetch` + `async / await`

---

## 📦 Struttura del progetto

```
EduQuiz/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── index.js
├── package.json
└── README.md
```

---

## 🔧 Utilizzo di Node.js ed Express

Il server è realizzato con **Node.js** e la libreria **Express**, che semplifica la gestione di:

- rotte HTTP (`GET`, `POST`)
- parsing del corpo delle richieste JSON
- gestione di file statici (HTML, CSS, JS)

---

## 🌐 API disponibili

### GET `/questions`
Restituisce la lista delle domande (senza la risposta corretta).

### POST `/start`
Inizia il quiz e azzera il punteggio.

### POST `/answers`
Riceve la risposta dell’utente, verifica se è corretta e aggiorna il punteggio.

### GET `/score`
Restituisce il punteggio corrente.

### POST `/questions`
Permette di aggiungere una nuova domanda al quiz.

---

## ⚙️ Setup locale

### 1️⃣ Clona il repository
```bash
git clone https://github.com/p4wlee/eduquiz.git
```

### 2️⃣ Entra nella cartella del progetto
```bash
cd eduquiz
```

### 3️⃣ Installa le dipendenze
```bash
npm install
```

### 4️⃣ Avvia il server
```bash
node index.js
```

### 5️⃣ Apri il browser
```
http://localhost:3000
```

---

## 📬 Contatti

- **GitHub:**  
  https://github.com/p4wlee

- **LinkedIn:**  
  https://www.linkedin.com/in/davide-paulicelli-00295222b/

---

## 📄 Licenza

Questo progetto è open source e disponibile sotto licenza **MIT**.
