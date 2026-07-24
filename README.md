# hybrid-propulsion-systems
Progetto individuale svolto per un esame del percorso magistrale: simulazione MATLAB/Simulink di un powertrain ibrido, con confronto tra diverse strategie di controllo e configurazioni dei componenti.

# Simulazione di Powertrain Ibrido — Confronto Architetture e Strategie di Controllo

Simulazione MATLAB/Simulink di un powertrain ibrido: confronto tra architetture (P2/P4), strategie di controllo ECMS e sostituzione progressiva dei componenti con dati reali.

## Obiettivo

Il progetto analizza e confronta diverse configurazioni di powertrain ibrido, partendo da un'architettura di riferimento con componenti forniti dai docenti, per poi valutare l'impatto di strategie di controllo alternative e di componenti reali (motore termico e macchina elettrica) sulle prestazioni e sui consumi.

## Fasi dell'analisi

1. **Confronto P2 vs P4** — ECMS non adattiva, motore termico fornito dai docenti e macchina elettrica di default
2. **ECMS adattiva vs non adattiva** — su architettura P2
3. **Guida predittiva** — su architettura P2
4. **Rubber engine sul motore termico** — scalatura del motore termico di riferimento
5. **Sostituzione con motore termico reale** — dati Geely
6. **Rubber engine sulla macchina elettrica** — scalatura della macchina elettrica di riferimento
7. **Sostituzione con macchina elettrica reale** — dati Toyota
8. **Modifica della batteria**
9. **Rubber engine su entrambi i componenti** — motore termico e macchina elettrica combinati

## Strumenti utilizzati

MATLAB, Simulink
