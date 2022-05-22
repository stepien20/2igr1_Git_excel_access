1.  Utwórz w bieżącym katalogu (Access) bazę o nazwie *nazwisko_imię_drogi*
1. Zaimportuj pliki *drogi.txt*, *kategorie.tx*t, *sieci.txt* oraz *stacje.txt* do bazy
1. Utwórz odpowiednie relacje między tabelami
1. Utwórz kwerendy:

   a. wyszukującą wszystkie autostrady (zawiera pola: id_drogi, nazwa, dlugosc, kategoria), posortuj wyniki wg. rosnącej długości drogi

   b. wyszukującą wszystkie drogi ekspresowe, które w nazwie mają ciąg znaków ***wice*** o długości ponad *100 km*, posortowane od najdłuższej do najkrótszej
   
   c. wyszukującą wszystkie drogi ekspresowe o długości pomiędzy wartościami, które wpisze użytkownik, przy których są stacje sieci ***Dobre Paliwo*** (zawiera pola: nazwa, kategoria, dlugosc, nazwa_sieci), posortowane alfabetycznie  wg nazwy drogi