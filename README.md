# Projekt Drona - Modelowanie 3D

## Opis Projektu
Projekt polegał na przygotowaniu szczegółowego modelu 3D części drona w programie **Autodesk Fusion 360**. Praca została wykonana na podstawie rysunków technicznych w ramach przedmiotu *Budowa i programowanie bezzałogowych statków powietrznych*.

Głównym celem zadania było precyzyjne odwzorowanie geometrii BSP (Bezzałogowego Statku Powietrznego) z zachowaniem standardów inżynierskich oraz przygotowanie plików do dalszej analizy, wizualizacji lub produkcji (druku 3D).

## Zawartość Repozytorium
W repozytorium znajdują się następujące pliki:
* **`projekt drona.stl`** – Model przygotowany do druku 3D (format stereolitografii).
* **`projekt drona.obj`** – Uniwersalny model siatkowy (Wavefront OBJ) zawierający geometrię.
* **`projekt drona.mtl`** – Biblioteka materiałów definiująca właściwości wizualne modelu.

## Specyfikacja Techniczna
Model został wykonany przy użyciu silnika **Autodesk ATF 15.8.0.0**. Zastosowano w nim następujące materiały (zgodnie z projektem w Fusion 360):
* **Włókno węglowe (splot skośny):** Główne elementy konstrukcyjne ramy, zapewniające lekkość i sztywność.
* **Aluminium (polerowane):** Elementy montażowe i wsporniki.
* **Stal (satynowa):** Śruby i elementy łączące.
* **Mosiądz (polerowany):** Tuleje oraz dystanse.
* **Farba metaliczna (żółta):** Elementy ostrzegawcze i identyfikacyjne.

## Instrukcja Użytkowania
1. **Import do Fusion 360:** Pliki można zaimportować do programu Fusion 360 w celu dalszej edycji.
2. **Druk 3D:** Plik `.stl` jest gotowy do wczytania do programów typu slicer (np. Cura, PrusaSlicer).
3. **Rendering:** Wykorzystaj pliki `.obj` oraz `.mtl` w programach takich jak Blender lub KeyShot, aby uzyskać fotorealistyczne wizualizacje.

---
