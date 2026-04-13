# bySaraYT

Repo statico per pubblicare contenuti bySaraYT su GitHub Pages.

## Struttura

- `index.html`: home generale del sito
- `health/`: playlist salute
- `health/index.html`: pagina playlist con elenco episodi
- `health/febbre/`: cartella episodio febbre
- `health/febbre/index.html`: landing dell'episodio
- `health/febbre/originale.html`: versione HTML originale
- `health/febbre/15min.html`: versione HTML estesa
- `health/febbre/scripts/febbre/`: materiali scaricabili e script di lavoro

## Come crescere

Per nuovi temi, crea una nuova cartella allo stesso livello di `health`, per esempio:

- `beauty/`
- `food/`
- `lifestyle/`

Dentro ogni playlist puoi mantenere questo schema:

- `index.html` per la playlist
- una cartella per ogni episodio, per esempio `febbre/`, `mal-di-gola/`, `tosse/`
- dentro ogni episodio:
  - `index.html`
  - versioni HTML del contenuto
  - `scripts/<argomento>/` per DOCX, TXT e materiali correlati

## Pubblicazione su GitHub Pages

1. Crea un repository GitHub con lo stesso contenuto di questa cartella.
2. Pusha il branch `main`.
3. In GitHub vai su `Settings` -> `Pages`.
4. In `Build and deployment`, scegli `Deploy from a branch`.
5. Seleziona branch `main` e cartella `/ (root)`.
6. Salva e attendi la pubblicazione.

Quando Pages e attivo, la home del sito sara `index.html`.

## Note

- Gli originali nella cartella sorgente locale non vengono modificati.
- Il sito e organizzato per playlist e episodi, cosi scala meglio quando i contenuti aumentano.
