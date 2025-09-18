# Jaka

Michał przygotowuje Własny System Kodów Paskowych (WSKP) i dlatego szuka liczb, których suma
cyfr jest większa od a i mniejsza od b. Przegląda kolejne liczby począwszy od 1 do 100000 (włącznie).
Napisz trójparametrową funkcję jaka. Pierwszym parametrem funkcji jest lewy koniec badanego
przedziału (a), drugim prawy koniec (b). Wynikiem funkcji jest n-ta kolejna liczba (określona przez
trzeci parametr), której suma cyfr jest większa niż a i mniejsza niż b. Jeśli taka liczba nie istnieje, to
wynikiem jest -1. Przyjmij, że trzeci parametr n wynosi co najwyżej 100, natomiast a < b < 40.

Przykłady:

* wynikiem jaka(1, 10, 4) jest 5,
* wynikiem jaka(1, 3, 100) jest -1.

W pierwszym przykładzie kolejne liczby spełniające warunek to 2, 3, 4, 5. 

W drugim przykładzie istnieje tylko 15 liczb spełniających warunek.