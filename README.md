# esgit
# Push e Pull in GitHub

## Cos'è un Push?

Un *push* è un'operazione utilizzata per caricare le modifiche locali di un repository Git sul server remoto (come GitHub). Quando esegui un push, invii i commit che hai creato nel tuo repository locale al repository remoto. Questo permette ad altri utenti di vedere e accedere alle tue modifiche.

### Comando

Il comando per eseguire un push è:

git push origin main
# Cos'è una Pull in GitHub

Una *pull* è un'operazione in Git e GitHub che consente di scaricare le modifiche apportate nel repository remoto e unirle con il tuo repository locale. Questa operazione è fondamentale per mantenere il codice sincronizzato tra diversi sviluppatori.

## Dettagli sull'Operazione di Pull

- **Recupero delle Modifiche**: 
  Il comando `git pull` esegue due operazioni: 
  1. Scarica le modifiche (fetch) dal repository remoto.
  2. Integra (merge) queste modifiche nel tuo branch corrente.

- **Comando**:
  ```bash
  git pull origin main
