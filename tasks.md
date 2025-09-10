1. EDA; Untersuche die Korrelation zwischen Persönlichkeitsmerkmalen under Bewertung von Filmen. Ggf. mit MDS / Isomap / PCA einen Psychologischen Score berechnen. Diesen Score kann man dann bewerten, inwiefern er mit den Filmewertungen korreliert (Pearson / Spearman / Mutual Information)
	- Die Beiden CSVs rankings und personality-data
2. Zeitreihen Vorhersage: PCA: jeweils Fortsetzen, dann Rückprojektion, Validierung mit Backtest (Train / Test Split bei 75% Zeit)
	- Datensatz: DAX oder Lufthansa Performance Daten
    - Idee: Nutze die erste Hälfte der Daten um PCA zu machen, dabei entstehen lineare Funktionen, die man fortsetzen kann
    - Damit kann der Zukünftige Kursverlauf vorhergesagt werden, und diese Vorhersage kann mit den tatsächlichen Daten verglichen werden
3. MDS oder Isomap, Dann Clustering (K-Means etc): Human Activity Recognition, dann Validieren
4. MNIST - 3 mal und dann Train / Test Vergleich der Klassifikation, FP, NP etc
	- MDS
	- PCA
	- Clustering
5. Weltkarte: Rekonstruire eine Weltkarte mit Isomap aus Daten von Flügen.