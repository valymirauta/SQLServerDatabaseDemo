# SQLServerDatabaseDemo
Creare baza de date si tabele in SQL Server
Se implementeaza o baza de date la o mica companie pentru evidenta angajatilor, clientilor, produselor si vanzarilor acesteia. 
Se creeaza urmatoarele tabele:
- Persoane  :
    - Angajati
    - Clienti
    
-Departamente
-Comenzi

  -Detalii comenzi
  
-Produse
 <img src="https://github.com/valymirauta/SQLServerDatabaseDemo/blob/master/companieER.JPG" width="350" height="256" title="Login">
 
 Cateva operatii cu datele din tabele:
 
 SELECT Nume, Prenume, Adresa , DataComanda FROM persoane p INNER JOIN Comenzi c ON p.Id=c.IdPersoana
 
 SELECT * FROM Produse
 
 UPDATE Produse SET PretUnitar = 6.5 WHERE Id=1
  
