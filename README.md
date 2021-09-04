# lcp-atlantgis-data
Least Cost Path Analysis AtlantGIS

Datensätze der fiktiven Insel AtlantGIS zur Durchführung einer Least Cost Path Analyse.

Das Datenarchiv ist in drei Teile gegliedert:
* 01_source-data enthält alle Quelldaten und deren Visualisierungen (=Karten).
    * 02_vector enthält eine GeoPackage-Datei mit Vektordaten (Flüsse, Küstenlinie, Landschaftsform, Start-/Endpunkt, Festungen etc.)
    * 01_raster enthält das Digitale Geländemodell (*Digital Elevation Model*, DEM) von AtlantGIS
    * 03_maps enthält kleinere Karten der Ausgangslage
* 02_processed-data enthält alle Datensätze, die im Lauf der Analyse erstellt wurden und als Zwischenschritte zu den Ergebnisdaten beigetragen haben.
    * 02_vector enthält die Buffer von Straßen und Flüssen sowie die Viewpoints der Festungen
    * 01_raster enthält alle rasterisierten Vektorlayer sowie die Kostenraster der fünf Kostenkategorien: Hang (*slope*), Landschaftsform (*landtype*), Straßennähe (*roads*), Gebietszugehörigkeit (*kingdoms*) und Sichtbarkeit (*viewshed*)
* 03_source-data enthält die Ergebnisdaten.
    * 01_raster enthält die vier berechneten, finalen Kostenraster mit unterschiedlicher Gewichtung
    * 02_vector enthält die vier berechneten Kostenpfade
    * 03_maps enthält alle Visualisierungen und Karten der Daten, die in der Analyse verwendet wurden
