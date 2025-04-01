# Machine-Learning-Project
# **Analisi di un Dataset sui Funghi** 🍄  

## **Descrizione del Progetto**  
Questo progetto ha l'obiettivo di analizzare due dataset contenenti dati tabulari su diverse specie di funghi.  
Lo scopo principale dell'analisi è quello di identificare modelli di machine learning in grado di prevedere se un fungo è **edibile** o **velenoso** in base alle sue caratteristiche.  

## **Dataset**  
Il dataset utilizzato contiene informazioni su 8000 campioni di funghi dal primo dataset e su 61000 campioni nel secondo, con 23 e 21 variabili che descrivono caratteristiche come:  
- Colore del cappello  
- Forma del gambo  
- Presenza di anelli   
- Odore  
- Altre caratteristiche biologiche 

Per rendere i modelli utilizzabili anche da utenti **non esperti di micologia**, sono state selezionate solo le variabili **facilmente riconoscibili da chiunque**, come il colore, la forma o il numero di anelli, evitando caratteristiche che richiederebbero un'analisi più tecnica.  


L'obiettivo è creare un modello predittivo per la classificazione binaria:  
- **Edibile (0)** ✅  
- **Velenoso (1)** ❌  

## **Analisi e Modelli**  
L'analisi del dataset include:  
✔️ **Esplorazione e Preprocessing**: Pulizia dei dati, gestione dei valori mancanti e codifica delle variabili categoriali.  
✔️ **Feature Selection**: Analisi dell'importanza delle variabili per ridurre la dimensionalità.  
✔️ **Modellazione**: Test di diversi algoritmi di machine learning, tra cui: 
   - **Baseline Model**
   - **Naive Bayes**
   - **Logistic Regression**
   - **Decision Tree** 🌳  
   - **Random Forest** 🌲🌲  
✔️ **Valutazione delle Performance**: Utilizzo di metriche come **accuracy**, **precision**, **recall** e **AUC-ROC**.  

## **Risultati**  
Il miglior modello identificato è stato **Random Forest** su entrambi i dataset, ha ottenuto buoni risultati anche utilizzando solo alcune delle variabili totali. 


## **Come Utilizzare il Codice**  
1️⃣ **Clonare il repository**:  
   ```bash
   git clone https://github.com/jackomazi/Machine-Learning-Project.git
   cd Machine-Learning-Project
