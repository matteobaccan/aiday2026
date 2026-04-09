# Il Vibecoding è morto: viva lo Spec-Driven Development

Repository per la presentazione "Il Vibecoding è morto: viva lo Spec-Driven Development" di Matteo Baccan, presentata alla **AI Day Conference 2026**.

## 📅 AI Day Conference 2026

**17 Aprile 2026 - Roma**

Innovating with AI and Cloud.

### Agenda

Programma dettagliato di AI Day Conference 2026.

**Data:** venerdi 17/04/2026  
**Location:** Roma (Rome)

#### Fasce comuni

| Orario | Attivita | Room |
|:---|:---|:---|
| 09:30 | Keynote (30 min) | Room 1 |
| 10:00 | Coffee Break (30 min) | Room 1 |
| 13:00 | Lunch (60 min) | Room 1 |
| 15:40 | Coffee Break (30 min) | Room 1 |

#### Sessioni parallele

| Orario | Room | Sessione | Speaker | Livello / Lingua |
|:---|:---|:---|:---|:---|
| 10:30 | Room 1 | Agent-to-Agent AI: orchestrare i Fabric Data Agent con Copilot Studio | Marco Caruso | Advanced, Italiano |
| 10:30 | Room 2 | Agentic AI senza catene: entra nel Microsoft Agent Framework | Maurizio Moriconi | Intermediate, Italiano |
| 11:20 | Room 1 | Gestione AI delle fatture: dal documento al modello predittivo | Alberto D'Angelo, Malvina Mattioni | Introductory and overview, Italiano |
| 11:20 | Room 2 | Il Vibecoding e morto: viva lo Spec-Driven Development | Matteo Baccan | Advanced, Italiano |
| 12:10 | Room 1 | AI Agents for Everyone: Creating No-Code Assistants in Microsoft 365 Copilot | Stefano Brusamolino, Beatrice Civelli | Intermediate, Italiano |
| 12:10 | Room 2 | Implementare Retrieval-Augmented Generation con Azure SQL e Microsoft Foundry | Andrea Saltarello | Intermediate, Italiano |
| 12:10 | Room Decision Makers | CxO, Decision Makers: Low Code | - | Decision Makers |
| 14:00 | Room 1 | Evoluzione di un sistema AI: da RAG a piattaforma ad agenti | Andrea Caglio, Luca Giudici | Intermediate, Italiano |
| 14:00 | Room 2 | Belli gli agenti... finche non li metti in produzione | Alessandro Mengoli | Intermediate, Italiano |
| 14:00 | Room Decision Makers | CxO, Decision Makers: No Code | - | Decision Makers |
| 14:50 | Room 1 | Hybrid AI Orchestration per Travel Booking Complessi | Andrea Belloni | Intermediate, Italiano |
| 14:50 | Room 2 | Umani & AI: la fabbrica del software del futuro | Michele Aponte, Antonio Liccardi | Intermediate, Italiano |
| 14:50 | Room Decision Makers | CxO, Decision Makers: Pro Code | - | Decision Makers |
| 16:10 | Room 1 | Potenziare gli agenti AI con ricerca semantica locale in .NET | Marco Milani | Advanced, Italiano |
| 16:10 | Room 2 | Agents Talking to Agents: Inside the A2A Protocol | Massimo Crippa | Intermediate, Italiano |
| 17:00 | Room 1 | Da GitHub Spark a .NET Aspire con un Copilot Agent: script deterministici + skills | Francesco Gallo | Intermediate, Italiano |

## 📄 Versioni della Presentazione

| File | Durata | Slide contenuto | Note |
|:---|:---|:---|:---|
| `presentation.md` | ~50 min | ~90 | Versione completa con tutti gli approfondimenti |
| `presentation30min.md` | ~30 min | ~50 | Versione compatta ottimizzata per slot da 30 minuti |

Entrambe le versioni includono 3 slide appendice (non presentate) con link e risorse per chi scarica le slide dopo l'evento.

## 📄 Contenuti della Presentazione

La presentazione esplora i limiti dell'approccio "Vibecoding" (programmare a sentimento con l'AI) e propone lo **Spec-Driven Development (SDD)** come metodologia professionale per lo sviluppo software assistito da AI.

### Punti Chiave

1. **Il Problema del Vibecoding**:
    * L'illusione di produttività data dagli script generati al primo colpo.
    * Problemi di scalabilità su sistemi Enterprise e legacy.
    * **Context Rot**: L'AI perde il filo e genera codice incoerente o allucinato man mano che la chat si allunga.
    * Allucinazioni verosimili: il rischio peggiore sono le risposte *credibili* ma tecnicamente sbagliate.

2. **Spec-Driven Development (SDD)**:
    * Le specifiche (in Markdown) diventano artefatti eseguibili.
    * L'AI agisce come un implementatore che segue un contratto preciso.
    * Vantaggi: Tracciabilità, Riproducibilità, Zero Context Rot.
    * Il ruolo dello sviluppatore cambia: da scrittore di sintassi ad **Architetto di Specifiche**.

3. **Framework e Strumenti**:
    * **BMAD**: Per contesti Enterprise complessi (21 agenti specializzati).
    * **GSD (Get Shit Done)**: Per sviluppatori singoli che vogliono velocità.
    * **GitHub Spec Kit**: Lo standard open source per l'ecosistema GitHub.
    * **Ralph Loop / Agent.OS**: Per flussi CI/CD autonomi ("Git as Memory").
    * **CodeSpeak**: Esempio radicale di linguaggio e workflow "spec-first" (AI-native).

4. **Workflow Pratico in 5 Step**:
    * Inizializzazione della cartella `.spec/` con contesto e convenzioni.
    * Drafting iterativo dei requisiti con l'AI.
    * Generazione della specifica tecnica con checkpoint umano.
    * Breaking down in task atomici e testabili.
    * Loop di implementazione con l'Agente AI.

5. **Applicazioni Concrete**:
    * SDD su legacy code (50.000 righe): analisi, protezione con test, refactoring incrementale.
    * Conformità e documentazione (GDPR, ISO 9001, AI Act).
    * ROI: riduzione tempi di debugging, efficienza token, onboarding più rapido.
    * **Benchmark SWE-CI**: Valutazione dell'AI sulla manutenibilità a lungo termine (zero-regression rate), che rende l'SDD una necessità assoluta.

## 🛠️ Tool Utilizzati

Questa presentazione è stata realizzata utilizzando:

* **BGE** (Brigata dei Geek Estinti) — Puntata 98 e 99 per gli spunti
* **Gemini** — Per la riformattazione
* **Nano Banana Pro** — Per le immagini
* **Claude** — Per la prima scaletta
* **NotebookLM** — Per i riassunti dei podcast e video
* **Antigravity** — Per gestire il progetto GitHub
* **Marp** — Per la generazione delle slide
* **Dario Ferrero** — Per l'analisi di CodeSpeak (<https://aitalk.it/>)

## 👤 Speaker

**Matteo Baccan**

* Sito web: [baccan.it](https://www.baccan.it)
* Quote: *"Smetti di chattare, inizia a governare."*
