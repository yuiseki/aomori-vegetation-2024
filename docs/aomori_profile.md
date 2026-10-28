# Aomori extract of 現存植生図2024: verification and profile

- polygons: 147,302 (147,302 MultiPolygon), CRS EPSG:6668, bbox lon 139.8581 to 141.6829, lat 40.2177 to 41.5562
- source files: {'veg2024bk2b.gpkg': 147302}
- cut: 145,015 polygons wholly inside Aomori kept as they are; 2,287 polygons that cross the boundary were clipped to it (none dropped); the clipped polygons had 4878.8 km2 before the cut and keep 618.2 km2
- area: 9643.475 km2 in EPSG:6678, against 9643.478 km2 for the N03 polygon of Aomori (99.99997%, difference -0.003 km2)
- area by 地域ブロック: 2 東北 9643.475 km2 (100.00% of N03)
- geometry validity: 0 invalid, 0 empty; fid unique: True
- overlaps: 106 pairs of polygons overlap by a sliver (largest 7.46e-10 square degrees, about 7 m2); not repaired
- NULLs: 0 in all columns

## 作成年度 (polygons)

| year | polygons |
| --- | ---: |
| 2000 | 26,821 |
| 2003 | 13,699 |
| 2012 | 12,677 |
| 2014 | 12,495 |
| 2015 | 2,969 |
| 2016 | 5,757 |
| 2017 | 6,683 |
| 2018 | 20,435 |
| 2022 | 45,766 |

## Legends whose name contains ブナ, ミズナラ, ナラ or コナラ

18 of the 142 legends present in Aomori; 22,340 polygons, 2897.6 km2 together (the legends overlap in meaning, do not read this as one class).

| code | name (original) | polygons | area km2 | ブナ | ミズナラ | ナラ | コナラ |
| --- | --- | ---: | ---: | :-: | :-: | :-: | :-: |
| 110100 | チシマザサ－ブナ群団 | 1,247 | 768.62 | x |  |  |  |
| 110102 | マルバマンサク－ブナ群集 | 2 | 0.00 | x |  |  |  |
| 110103 | スギ－ブナ群落 | 106 | 5.74 | x |  |  |  |
| 110500 | ミズナラ群落（日本海型） | 8 | 0.37 |  | x | x |  |
| 110501 | ホツツジ－ミズナラ群集 | 164 | 4.30 |  | x | x |  |
| 130203 | モミ－イヌブナ群集 | 1 | 0.04 | x |  |  |  |
| 140201 | ブナ－ヒノキアスナロ群落 | 423 | 76.81 | x |  |  |  |
| 190100 | ウラジロヨウラク－ミヤマナラ群団 | 112 | 3.71 |  |  | x |  |
| 190101 | ミヤマナラ群落 | 60 | 8.31 |  |  | x |  |
| 220100 | ブナ－ミズナラ群落 | 3,153 | 796.15 | x | x | x |  |
| 220103 | オオバクロモジ－ミズナラ群集 | 8,156 | 711.03 |  | x | x |  |
| 220104 | ブナ二次林 | 778 | 101.66 | x |  |  |  |
| 220106 | キタコブシ－ミズナラ群集 | 735 | 71.08 |  | x | x |  |
| 220500 | コナラ群落（V） | 3,222 | 188.56 |  |  | x | x |
| 220501 | オクチョウジザクラ－コナラ群集 | 1,848 | 62.28 |  |  | x | x |
| 220505 | ホソバヒカゲスゲ－コナラ群集 | 1,624 | 51.80 |  |  | x | x |
| 221100 | ミズナラ群落（V） | 700 | 47.11 |  | x | x |  |
| 410101 | クリ－コナラ群集 | 1 | 0.02 |  |  | x | x |

The match is by substring on the original name. ナラ also matches names that are neither ミズナラ nor コナラ: ウラジロヨウラク－ミヤマナラ群団 (190100), ミヤマナラ群落 (190101). ブナ also matches イヌブナ, another species: モミ－イヌブナ群集 (130203).
The full list of Aomori legends is `legend_aomori.tsv`.

## 作成年度 of the polygons of those legends

| year | polygons |
| --- | ---: |
| 2000 | 3,877 |
| 2003 | 2,613 |
| 2012 | 1,584 |
| 2014 | 1,972 |
| 2015 | 563 |
| 2016 | 1,309 |
| 2017 | 1,223 |
| 2018 | 4,062 |
| 2022 | 5,137 |
