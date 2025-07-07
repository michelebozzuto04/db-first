Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Cosa consegnare?
create un file readme come fatto stamattina in classe con la struttura della tabella.

## Table name: Cars

- id | INT - PRIMARY_KEY AUTO_INCREMENT NOTNULL UNIQUE
- marca | VARCHAR(20) NOTNULL
- modello | VARCHAR(35) NOTNULL
- prezzo | DECIMAL(8, 2) NOTNULL
- anno | YEAR NULL
- km | INT NOTNULL
- condizione | VARCHAR(30) NULL
- targa | VARCHAR(7) NULL
- cilindrata | INT NULL
- cavalli | INT NULL
- tipo | VARCHAR(30) NULL
- porte | INT NULL
- note | TEXT NULL