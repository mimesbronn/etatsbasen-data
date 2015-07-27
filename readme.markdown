# etatsbasen-data

Inneholder en csv fil med en utdatert liste over offentlige
virksomheter i Norge. Opprinnelig er datasettet fra etatsbasen
tilknyttet norge.no / Difi. Dessverre har dette datasettet ikke blitt
oppdatert siden 2012 da arbeidet med norge.no har vært uavklart.

Datasettet er opprinnelig basert på
[åpne datasett fra Difi](http://data.norge.no) og er underlagt
[Norsk lisens for offentlig data (NLOD)](http://data.norge.no/nlod/en/1.0). Datagrunnlaget
ble sist oppdatert i 2012, og blir ikke lenger vedlikeholdt av Difi.

Feil kan rapporteres via pull request her på github, via issues eller
via epost på [https://www.mimesbronn.no/help/contact](kontaktsiden på
Mimes brønn).

# EKSEMPEL

``` csv
#tailid,email,name_nb,name_nn,name_en,url_nb,url_en,orgstructid,orgid,kommunenummer,parentid
41943,post@oslo-universitetssykehus.no,DPS Søndre Oslo - Holmlia - distriktspsykiatrisk senter,DPS Søndre Oslo - Holmlia - distriktspsykiatrisk senter,DPS Søndre Oslo District Psychiatric Centre - Holmlia,http://www.oslo-
universitetssykehus.no/omoss/avdelinger/dps-sondre-oslo/Sider/enhet.aspx,,39,,,42285
23842,nav.kontaktsenter@nav.no,NAV Voss,NAV Voss,NAV Voss,http://www.nav.no/Lokalt/Hordaland,http://nav.no/page?id=1073743655,37,,,26064
23844,nav.arbeidslivssenter.hordaland@nav.no,NAV Arbeidslivssenter Hordaland,NAV Arbeidslivssenter Hordaland,NAV Employment Support Centre (Hordaland),http://nav.no/805321255.cms,http://nav.no/page?id=1073743655,36,,,2606
4
```
# lisens

Norwegian Licence for Open Government Data (NLOD)
http://data.norge.no/nlod/en/1.0

eller

Open Data Commons Attribution License (versjon 1.0)
http://opendatacommons.org/licenses/by/1-0/

eller

Open Government Licence (versjon 1.0)
