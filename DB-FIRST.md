| COLONNA               | TIPO        | ATTRIBUTI                   |
| --------------------- | ----------- | --------------------------- |
| id                    | bigint      | PRIMARY_KEY, AUTO_INCREMENT |
| marca                 | varchar(30) | NOT NULL                    |
| modello               | varchar(30) | NOT NULL                    |
| porte                 | tinyint(1)  | NULL, UNSIGNED              |
| colore                | varchar(20) | NULL                        |
| km_percorsi           | smallint    | NULL, UNSIGNED              |
| anno_immatricolazione | year        | NOT NULL                    |
| alimentazione         | char(1)     | NOT NULL                    |
| cambio                | char(1)     | NULL                        |
| cilindrata            | smallint    | NOT NULL, UNSIGNED          |
| posti                 | tinyint     | NULL, UNSIGNED              |
| prezzo                | float(8,2)  | NULL                        |
| tipologia             | varchar(20) | NULL                        |
| targa                 | char(7)     | NULL, UNIQUE                |
