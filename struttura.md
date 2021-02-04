<!-- 
Istruzioni:
Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  
Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato.
-->

# database nome: Games
# nome tabella: Videogames
- id / BIGINT PRIMARYKEY / NOTNULL / AUTO_INCREMENT UNIQUE
- codice_articolo / string VARCHAR(13) / NOTNULL / UNIQUE
- titolo / string VARCHAR(150) / NOTNULL
- lingua_interfaccia / string VARCHAR(30) / NOTNULL
- lingua_voci / string VARCHAR(30) / NOTNULL
- lingua_sottotitoli / string VARCHAR(30) / NOTNULL
- sviluppatore / string VARCHAR(15) / NOTNULL
- editore / string VARCHAR(15) / NOTNULL
- genere / string VARCHAR(15) / NOTNULL
- img_copertina / string VARCHAR() / NULL
- descrizione / string TEXT / NULL
- disponibile / number TINYINT / NOTNULL
- quantità / number SMALL / NULL
- prezzo / number FLOAT(3,2) / NOTNULL
- data_uscita / date DATE / NULL
- piattaforma / string VARCHAR(15) / NOTNULL
- requisiti_di_sistema / string TEXT / NULL
- sistema_di_classificazione / string VARCHAR(10) / NOTNULL
- punteggio_utenti / number TINYINT / NULL
