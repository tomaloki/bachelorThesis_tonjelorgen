# Bachelorprosjekt vår 2022

## Gruppe 9

#### Skrevet og utført av:
Navn: Bernadette Fanni Finheim <br />
Studentnummer: S341857 <br />
Epost: fanni.szeplaki@gmail.com 

Navn: Hanna Bækken Nilsen <br />
Studentnummer: S341879 <br />
Epost: hannabn00@gmail.com 

Navn: Tonje Martine Lorgen Kirkholt <br />
Studentnummer: S341844 <br />
Epost: tonjelorgen@gmail.com 

Navn: Helene Birkeflet Prescott <br />
Studentnummer: S341873 <br />
Epost: heleneprescott@gmail.com


## Sammendrag

Denne rapporten er et endelig resultat av bachelorprosjektet til fire Dataingeniørstudenter ved fakultet for Teknologi, Kunst og Design (TKD) på OsloMET.
Arbeid og ferdigstillelse av oppgaven har blitt gjennomført i løpet av våren 2022, med Forzasys som oppdragsgiver. Deres overordnede mål er å utvikle en
funksjon for prediksjon av skade som kan implementeres i applikasjonen pmSys, brukt for loggføring av velværeparametere fra idrettsutøvere. Rapporten presenterer
prosessen med å utforske løsninger innen maskinlæring, og videre predikere en utøvers opplevde dagsform basert på historisk data. Det har blitt fokusert på tre 
valgte maskinlæringsmodeller; Random Forest, Autoregressive Integrated Moving Average og Long Short-Term Memory. Samtidig har gruppen sett på om resultatet potensielt
kan brukes som et skadeforebyggende verktøy for både trener og atlet. På denne måten vil man kunne fremme videre progresjon og helse for idrettsutøveren. 
Med en gjennomgående drøfting av valgene som har blitt tatt i løpet av prosjektperioden, forklares arbeidet som er gjort tydelig for leseren. Vi gjøre rede for beslutninger
angående teknologi, fremgangsmåter og modeller presentert i rapporten. Den endelige konklusjonen vil baseres på det helhetlige forskningsarbeidet, hvor vi tilbyr alternativer
og forslag for fremtidige mål. Her vil vi diskutere det gjennomførte arbeidet, samt gi et innblikk i refleksjoner som ble gjort i sluttprosessen.


### Informasjon om datasett og kjøring av kode
På grunn av nødvendige begrensninger er det ikke ønskelig fra oppdragsgiver sin side at datasettene brukt i
dette prosjektet er lagt ved. Siste opplasting på GitHub viser derimot hvordan koden så ut ved
siste kjøring, og det har blitt godkjent fra oppdragsgiver at utsnitt fra datasett kan vises.
Om det blir forsøkt å kjøre koden på nytt, vil man ikke få en brukbar output på grunn av
manglende datasett.

## Referanser
### Random Forest
https://www.cienciadedatos.net/documentos/py27-time-series-forecasting-python-scikitlearn.html

https://joaquinamatrodrigo.github.io/skforecast/api/ForecasterAutoreg.html

https://joaquinamatrodrigo.github.io/skforecast/api/ForecasterAutoregCustom.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

### ARIMA
https://www.projectpro.io/article/how-to-build-arima-model-in-python/544

https://neptune.ai/blog/arima-sarima-real-world-time-series-forecasting-guide

https://medium.com/p/bb83e49210cd

https://machinelearningmastery.com/time-series-data-stationary-python/

https://www.machinelearningplus.com/time-series/augmented-dickey-fuller-test/

https://medium.com/@cmukesh8688/why-is-augmented-dickey-fuller-test-adf-test-so-important-in-time-series-analysis-6fc97c6be2f0

https://medium.com/analytics-vidhya/time-series-forecasting-sarima-vs-auto-arima-models-f95e76d71d8f

https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/


### LSTM

https://towardsdatascience.com/lstm-time-series-forecasting-predicting-stock-prices-using-an-lstm-model-6223e9644a2f

### Dummy Modell

https://www.geeksforgeeks.org/dummy-regressor/

https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyRegressor.html


### Injury Prediction - Logistic Regression

https://alancouzens.com/blog/injury_prediction2.html 
