# Leier_makra
Zestaw makr do pracy z Allplanem, arkuszami kalkulacyjnymi i innymi narzędziami w Libre Office Calc.


'==========================================
'                 ABOUT
'==========================================

'
'  OPIS DLA BASIC ADDONS BUILDER:
' Makra wspomagające konwersję zestawień prętów i siatek zbrojeniowych z Allplana na pliki produkcyjne
' stosowane w LEIER POLSKA - Zakład w Malborku.
' Makra wymagają pliku "Siatki Leier do kopiowania.xlsx" w katalogu "C:\User\Public\Documents".
'

' +++++++++++++++++++++++++++++++++++++++++++++++
'	Moduł pomocniczy do określenia wersji makra,
'	pomocy w instalacji oraz listy zadań do zrobienia
' +++++++++++++++++++++++++++++++++++++++++++++++

' +++++++++++++++++++++++++++++++++++++++++++++++
'	INSTALACJA:
'   1. Arkusz 'SIATKI LEIER do kopiowania.xlsx" skopiuj do katalogu:
'		C:\Users\Public\Documents
'	W tym arkuszu należy wpisać nazwy siatek wraz z średnicami,
'	roztawami i polem zbrojenia wzdłuż i w poprzek długości siatki.
'
'	2. Zainstaluj rozszerzenie LEIER_ZestAllplan-X.X.X.oxt.
'
'	3. Dodaj menu uruchamiające makra za pomocą polecenia:
'	Narzędzie -> Dostosuj
'	Zalecana struktura menu poniżej.
'
' +++++++++++++++++++++++++++++++++++++++++++++++
'	ZALECANA STRUKTURA MENU:
'	- LEIER:
'				|-> Siatki:
'						-> Ciężary siatek wg średnic
'						-> Edytuj "Siatki Leier do kopiowania.xlsx"
'						-> SEPARATOR
'						-> Sortuj siatki po szerokości
'						-> Sortuj siatki po długości
'						-> SEPARATOR
'						-> Puste zest siatek
'						-> Zest siatek z CSV od MATa
'						-> SEPARATOR
'						-> Wstaw nr zlecenia i datę dostawy
'
'			Pręty
'						-> Puste zest prętów
'						-> Zest prętów z CSV od MAATa
'
'				|-> Dla MATA:
'								|-> Eksportuj zest siatek do CSV dla MATA
'								|-> Eksportuj zest prętów do CSV dla MATA

'				|-> KALKULACJE:
'								|-> Aktualizuj cennik
'								|-> Podsumowanie kalkulacji
'								|-> Napraw formułę transportu (B98)
'
'				|-> Info:
'								|-> Wersja (makro JakaWersja)
'
' +++++++++++++++++++++++++++++++++++++++++++++++
