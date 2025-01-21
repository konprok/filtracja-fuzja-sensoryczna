# Filtracja i Fuzja Sensoryczna

## Projekt prezentuje zastosowanie rozszerzonego filtru Kalmana w celu fuzji danych z czujników, żyroskopu oraz akcelerometru.

### Informacje ogólne

Na ramieniu robota został zamontowany czujnik SensorTile.box.

Podczas ruchu robota zarejestrowano przebiegi z czujników (akcelerometr, żyroskop, magnetometr, czujnik temperatury i czujnik wilgotności) oraz położenie i orientację robota.

Nagranie z eksperymentu można obejrzeć tutaj: https://youtu.be/6O0fGh5dt5Q

### Dane

Plik train.csv zawiera dane z czujników oraz dane referencyjne. Pierwszy wiersz stanowi nagłówek. Następnych 7000 wierszy to dane w następującej kolejności: identyfikator próbki, wektor czasu, akcelerometr (XYZ), żyroskop (XYZ), magnetometr(XYZ), czujnik temperatury, czujnik wilgotności, dane referencyjne o orientacji z robota (roll, pitch, yaw).

Plik train.csv zawiera dane z czujników. Pierwszy wiersz stanowi nagłówek. Następnych 15000 wierszy to dane w następującej kolejności: identyfikator próbki, wektor czasu, akcelerometr (XYZ), żyroskop (XYZ), magnetometr(XYZ), czujnik temperatury, czujnik wilgotności.

#### Pliki

train.csv - zbiór uczący
test.csv - zbiór testowy
sample-submission - zbiór wynikowy