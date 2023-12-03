
# Miejsca aktywności weekendowej we Wrocławiu - portal mapowy.

Portal mapowy przedstawia miejsca aktywności weekendowej we Wrocławiu oraz wyniki geonkiety przedstawiającej preferencje ankietowanych dotyczących tych miejsc.
Portal mapowy opracowano za pomocą oprogramowania [QGIS](https://qgis.org/pl/site/index.html) z zainstalowaną wtyczką [qgis2web](https://plugins.qgis.org/plugins/qgis2web/) oraz oprogramowania [Leaflet](https://leafletjs.com).

Link do ankiety: https://arcg.is/jzGWb

Portal przygotowany został przez studentów IV roku Politechniki Wrocławskiej na kierunku Geodezja i Kartografia w ramach projektu semestralnego z przedmiotu Systemy Geoinformacyjne.


## Funkcje portalu

- Panel włączania i wyłączania warstw;
- Rozwijalna mapa poglądowa;
- Tryb pełnoekranowy;
- Podziałka liniowa;
- Legenda;
- Pasek powiększania i zmniejszania widoku;
- Współrzędne miejsca kursora;
- Okna podręczne po kliknięciu na wybrany obiekt.

## Dostępne warstwy
- Aktywności weekendowe - miejskie;
- Aktywności weekendowe - sportowe;
- Ulice;
- Budynki;
- Przystanki;
- Granice osiedli;
- Podkład mapowy - ESRI Satellite.

## Źródła danych
- BDOT10k (budynki i ulice);
- OpenStreetMap (miejsca aktywności i podkład mapy podglądowej);
- wrosip.pl (granice osiedli);
- ESRI Satellite (podkład głównej mapy).

## Wykorzystane Plug-iny
Do sporządzenia portalu wykorzystano następujące plug-iny:
 - [Leaflet.fullscreen](https://github.com/brunob/leaflet.fullscreen) przez brunob;
 - [Leaflet.Legend](https://github.com/ptma/Leaflet.Legend) przez ptma;
 - [Leaflet-MiniMap](https://github.com/Norkart/Leaflet-MiniMap) przez Norkart;
 - [Leaflet.MousePostion](https://github.com/ardhi/Leaflet.MousePosition) przez ardhi.


## Licencja

[GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.txt)
