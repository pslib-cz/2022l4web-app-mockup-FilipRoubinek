# Pirate Island Travel

## UI/UX

User Interface je lehká vektorová grafika optimalizovaná na obraz 1920x1080. Další velikosti je nutno dodělat (samotné soubory s UI jsou nahrané ve složce PirateRPG_Mockup)

## Příběh hry

V této hře se hráč stává pirátem. Začíná na ostrově, kde si zakoupí loď a základní potřeby a vydá se na cestu. Každý ostrov se napojuje na další ostrovy, takže je vždy kam plout, ale pozor, aby nedošly suroviny, protože se dál plout nemůže!

## Suroviny

Suroviny jsou potřeba k vyražení na cestu. Suroviny se sbírají automaticky po úspěšném přistání na ostrově.

### Pitná voda
Nejrychleji ubývající surovina, které je vždy potřeba udělat vysoká zásoba. Existuje šance na event, který doplní část zásoby vody

### Potraviny
Stejně jako pitná voda, je vždy nutno udělat vysokou zásobu. Potraviny však vydrží 1,5x dýl jak zásoby vody (při stejném množství)

## Karty

Hra je hraná systémem karet. Kromě vody a potravin jsoou veškeré předměty označeny kartama. Veškeré karty se nachází v inventáři, odkud je možno je zahrát. Karty jsou rozřazeny do tříd, kdy 1. třída je nejlepší.

![Card Example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/PirateRPG_Mockup/Card_Mockup_1st_Rifle.svg)

### Materiály na opravu
Některé materiály (hřebíky, látky) je možno zakoupit pouze na nezávislých ostrovech. Některé materiály jsou dostupné i na prázdných ostrovech, na kterých je možno za pomocí určitých nástrojů nasbírat a použít.

### Nástroje
Během plavby je nutno opravovat loď. Ve hře se nachází 2 typy nástrojů. Na sbírání a upravování materiálů (sekery, pily, hoblík) a na přímé opravování (kladiva, jehly na šití). Nástroje na opravu jsou karty bez tříd a jsou nevyčerpatelné.

### Zbraně

Zbraně se dělí na dva typy. Zbraně na blízko a na zbraně na dlouhou vzálenost. Zbraně na blízko mají obecně nižší šanci na poškození nepřítele, ale nevyžadují žádné náboje. Zbraně na dálku mají vždy víc jak 60 % na šanci poškození. Zbraně na dálku vyžadují náboje. Ty se dají zakoupit na obchodních ostrovech

## Plavby
Na prvním ostrově se zakoupí jedna z několika map k dalšímu ostrovu, je možno zakouipit jen jednu mapu. Na dalším ostrovu jsou zadány informace k dalšímu ostrovu. Na některých ostrovech je možnost cestovat na více ostrovů. Vždy je možnost cestovat na předchozí ostrovy. Plavby trvají určitou dobu (maximálně 7 minut).

## Mapa
Mapa slouží k rychlé orientaci v progresu hry. Cestování je možno vždy jen po jednom ostrově. Ostrovy jsou postupně odhalovány postupem hrou. Další ostrov na mapě je bez speciálního označení a následně po doražení na ostrov je označem typem ostrova (nezávislý, pirátský, královský).

### Ostrovy

Ve hře se nachází několik typů ostrovů, každý má určitou funkci

#### Královský ostrovy

Královské ostrovy jsou vynucené souboje. Je možno bojovat, nebo se vrátit na předchozí ostrov. Útěk má ale menší možnost na úspěch, než u pirátského ostrova.

#### Pirátské ostrovy

Pirátské ostrovy prezentují nejvíce možností ze všech ostrovů. Je možno bojovat s nepřátelskými piráty, útéct na předchozí ostrov, nebo za určitou cenu vstoupit na černý trh, kde se nachází cené předměty vysokých úrovní, ale za vysoké ceny.

#### Nezávislé ostrovy

Na nezávislé ostrovy není možno útočit. Nabízejí však možnost nabrat suroviny a zakoupit nové karty.

##### Obchodní ostrovy

Obchodní ostrovy nabízejí zakoupit veškeré předměty nacházející se ve hře. V průměru se nachází v obchodech předměty 5. až 3. třídy, někdy se mohou objevit předměty 2. třídy.

##### Opuštěné ostrovy

Opuštěné ostrovy jsou jen zastávkou v průběhu cesty. Je na nich možno získat suroviny potřebné k pokračování v cestě.

## Příklady vzhledu hry

### Menu

![Menud example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/70a00e3d013d3eda9c3d389f73cff251aaece062/PirateRPG_Mockup/Menu.svg)

### Shop

![Shop Example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/Shop_Example.svg)

### Inventory

![Inventory Example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/Inventory_Example.svg)

### Map

![Map Example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/Map_Example.svg)

### Island Options and Fight

![Island Options](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/Island_Option_Example.svg)

![Island Fight](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/Fight_Example.svg)

### Pause

![ESC example](https://github.com/pslib-cz/2022l4web-app-mockup-FilipRoubinek/blob/9201648e04efdab777527bb0570fe29c6da068e1/Kompletace/ESC_Example.svg)
