# Podświetlane paragrafy
Rozwiązanie pierwszego zadania domowego na bootcampie Frontend, infoShare Academy.

## Opis zadania:
Stwórzcie takie selektory, aby:
- po najechaniu na box oba paragrafy robiły się żółte
- po najechaniu na górny paragraf robił się on czerwony ( a drugi żółty)
- po najechaniu na dolny paragraf robił się on niebieski ( a pierwszy żółty)

## Uwagi

Nie jestem pewny czy to jest najładniejsze rozwiązanie dla dwóch ostatnich punktów.
```css
.box:hover .red:hover{
    color: red;
}
```