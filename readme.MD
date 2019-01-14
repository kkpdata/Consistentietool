# Versies en aanpassingen

11-01-2019: Consistentietool v1.0 toegevoegd.

# Doel

Het controleren van de onderlinge consistentie van parameters uit berekeningen voor ongedraineerde schuifsterkte. 

# Installer

Een installer kan worden gedownload bij de Release Consistentietool v. 1.2 (https://github.com/kkpdata/CPT-Tool/releases/tag/CPT-Tool)

# Gebruik en functionaliteit

Voor het faalmechanisme macrostabiliteit wordt in het WBI het SHANSEP model gebruikt voor het bepalen van de ongedraineerde schuifsterkte van slecht doorlatende grondlagen. Naast de SHANSEP-parameters wordt in WBI ook gebruik gemaakt van sonderingen om de ongedraineerde sterkte af te leiden. Dit gebeurt d.m.v. een project-specifiek afgeleide relatie (Nkt factor) tussen genormaliseerde conusweerstand (uit sonderingen) en ongedraineerde schuifsterkte (uit overgeconsolideerde laboratorium proeven). Om dit werkproces te ondersteunen zijn tools ontwikkeld voor het afleiden van de correlatiefactor ([Nkt Tool](https://github.com/kkpdata/Datatools/tree/master/Scripts-rijkswaterstaat-iris/NKT-Tool%20v.1.0)) en voor de afleiding van de ongedraineerde schuifsterkte uit sonderingen ([CPT Tool](https://github.com/kkpdata/CPT-Tool)). 

Het is van belang dat de berekende ongedraineerde schuifsterkte van beide manieren (1) berekend volgens SHANSEP en (2) via de relatie met sonderingen consistent met elkaar zijn. Vaak vereist dit een aantal iteratieve stappen om te komen tot een consistente set van (karakteristieke waarden van) parameters. Om het proces van consistent maken te ondersteunen is een nieuwe tool ontwikkeld, welke de resultaten van laboratorium proeven en meerdere geanalyseerde sonderingen van een project gezamenlijk toont. In deze Consistentietool is de functionaliteit van de Nkt tool geïntegreerd, waardoor de Nkt tool op termijn kan vervallen.

# Technische informatie

De Consistentie tool is een aanvulling op de reeds bestaande CPT en Nkt tools. De Consistentie Tool maakt alleen gebruik van met de CPT Tool geanalyseerde bestanden, waardoor ook installatie van de CPT Tool benodigd is. De Consistentie Tool is ontwikkeld in dezelfde programmeeromgeving en maakt dus gebruik van dezelfde achtergrondbestanden als de CPT Tool en Nkt Tool. De installatie van de Consistentie Tool is gelijk aan de installatie van de CPT Tool; hiervoor wordt verwezen naar de handleiding van de CPT en Nkt tools (Van der Krogt & Teixeira, 2018). Om de CPT Tool te laten werken dient MATLAB te zijn geïnstalleerd. Informatie hierover is te vinden in het tekstbestand dat is opgenomen in de bestandsmap van de CPTtool.  

# Achtergrondinformatie

Betreft versie 1.0, uit december 2018.

# Contactpersoon
[Iris van de Kerk](https://github.com/orgs/kkpdata/people/IvdK), (Iris.vande.kerk@rws.nl) [Rijkswaterstaat-WVL](https://www.rijkswaterstaat.nl/over-ons/onze-organisatie/organisatiestructuur/water-verkeer-en-leefomgeving/index.aspx)
[Harm Rinkel](harm.rinkel@rws.nl) [Rijkswaterstaat-WVL](https://www.rijkswaterstaat.nl/over-ons/onze-organisatie/organisatiestructuur/water-verkeer-en-leefomgeving/index.aspx)
