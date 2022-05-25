
# database
ce projet est une création de base de donné pour une entreprise de location de film dans le but de rendre facile la gestion de la clientèle puis les entres et les sorties de films
voici comment faire vos requettes SQL:  
   pour ajouter un client:INSERT INTO identité (nom,prenom,email)value "awesso, lotye ,lotyeawesso@gmail.com"
   pour ajouter un film: INSERT INTO films (nom du film,cathegorie du film,duree,date de sortie) value" swaat ,action,4h,2008"
     pour suprimer un film:DELETE FROM(films WHERE id = 1) value "swaat ,action,id=1
     pour modifier un film:ALTER TABLE user MODIFY COLUMN VARCHAR(45)  value:"cathegorie ,gladiator, 5h"
     pour modifier un client: ALTER TABLE user MODIFY COLUMN VARCHAR(45) value " Fatou, Dione ,fatoudione @gmail.com"
     pour suprimer un client :DELETE FROM ( identite WHERE id = 1) value " awesso,lotye,"
     pour afficher les trois derniers films :SELECT FROM des clients_films ORDER BY id film DESC LIMIT 3 
tanks
