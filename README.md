# Tp1
Mon premier projet 

         Algorithmique et Programmation 1
                         TP N° 1

Exercice 1 :
ALGORITHME code PIN 
VAR constante , tentative, PIN : entier 
DÉBUT
Constante <--0000
Tentative<--3
Tantque (tentative<3) faire 
     Écrire ("saisie le code PIN")
     Lire ( PIN)
                Si ( PIN<--Constante ) alors  
                   Écrire ("code correct, l'opération se fait avec succès")
                      Sinon Si("PIN #Constante ") alors 
                        Écrire ("erreur, il reste (3-tentative) tentatives")
                           Sinon écrire ("la carte SIM est bloqué ")
                                    Fin Si 
                         Fin Si 
          Fin tantque 
  FIN
Exercice 2: 
ALGORITHME  échange des valeurs de deux variables 
VAR  N1,N2: entier 
DÉBUT 
Écrire ("donner la valeur de N1")
Lire (N1)
Écrire ("donner la valeur de  N2 ")
Lire (N2)
N1<--N2
N2<--N1
Lire ("la valeur de N1 est : "",N2, et la valeur de N2 est :"",N1")
FIN 
Exercice 3:  
1-
ALGORITHME Euclide
VAR n1,n2, PGCD: entier
DÉBUT 
Écrire ("saisie deux nombres")
Lire ("n1 , n2 ")
Tantque (n2#0) faire 
n1 <-- n2
n2 <--n1modn2
Écrire ln("le pgcd de n1 et n2 est "", n1) 
Fin tantque 
FIN 
2-
ALGORITHME Euclide
VAR n1,n2, PGCD: ENTIR 
Fonction PGCD (A , entier ; B, entier ): Entier 
    Si (B=0) alors 
       Retourner A
     Sinon retourner PGCD (B , AmodB)
   Fin Si 
Fin fonction 
DÉBUT 
Écrire ("saisie deux nombres")
Lire ("n1 , n2 ")
Pgcd <-- Fonction PGCD (n1 , n2 ) 
Écrire ("le Pgcd de n1 et n2 est "", Pgcd) 
FIN 
