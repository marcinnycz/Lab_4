Zad 1.
Stworzyć wektor dowolnego typu.
W pętli dodawać do wektora po jednym elemencie. Obserwować zmiany rozmiaru (size), pojemności (capacity), oraz adresu w pamięci, gdzie znajduje się wektor (data).
Dlaczego adres początku ulega zmianie pomimo tego, że dodajemy elementy na koniec?

Zad 2.
Stworzyć listę zakupów:
(Po każdym podpunkcie wypisać zawartość listy)

1. Stworzyć pustą listę.
2. Dodać kilka elementów do listy: "czekolada", "mleko", "jajka", "pomidory", "banany", "kurczak".
3. Usunąć pierwszy element z listy.
4. Dodać element "ser" na początek listy.
5. Znajdź w liście "mleko" i zamień na "mleko bez laktozy".
6. Wstaw element "gruszki" przed "banany".
7. Wypisz zawartość listy w odwrotym kierunku (użyj rbegin() i rend()).

Zad 3.
Dana jest struktura typu map, która zawiera stan magazynu kwiaciarni.
Kluczem jest nazwa kwiatka, a wartość to liczba kwiatków tego typu w magazynie.
W zadaniu należy:

1. Znaleźć i wypisać na ekran wszystkie kwiatki, których liczba na stanie jest mniejsza niż 10.
2. Usunąć wszystkie kwiatki na literę 'K' (użyć upper_bound(), lower_bound() i erase()).
3. Znaleźć za pomocą find() kwiatek "tulipan" i wypisać ilość tulipanów na ekran.
4. Stworzyć własną kwiaciarnię (kolejny obiekt map), dodać kilka dowolnych kwiatków, a następnie zamienić zawartości kwiaciarni ze sobą (funkcja swap()).
