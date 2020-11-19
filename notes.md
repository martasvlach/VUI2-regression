#### Představení
*Říci jakým tématem se budeme zabývat + něco, že se to nebudeme snažit uspat matematikou v pozadí, ale představit věci na co je to možné použít, na co se to hodí etc.*
***

#### Regrese v různých vědních odvětvích
*Uvést širší kontext, zmínit že regrese se objevuje srkze mnoho vědních oborů a uvést následující příklady.*

- **Lékařství** - Stav kdy nemoc začíná usputovat z jejích nejtěžšího průběhu do mírnějších projevů.

- **Právo** - (postihy) stav kdy například pojišťovna vymáhá po pachateli zpětně částu, kterou uhradila v rámci povinného ručení, pokud byly zjištěny nové zkutečnosti.

- **Filozofie** - Nekonečné zjišťování příčiny příčiny (obdoba rekurze) -> filozofický problém hledání počátku všeho.

- **Softwarové inženýrství** - Testy které ověřují zda dříve otestovaný software stále funguje správně i po zavedení změn (nová verze, refaktorizace ..).
---
#### Regresivní analýza

*Nejdříve zmínit tyhle příklady, potom přejít k formálnější definici co je v jupiteru.*

Regresivní analýzu používáme na denní bázi i běžném životě, aniž by jsme si to přímo uvědomovali. Typickou jednoduchou podobou je rozhodování na základě předchozích zkušeností v dané problematice, či predikce vývoje počasí v následujících 30 minutách na základě shlédnutí předpovědi počasí v televizi a aktuálním pohledem na oblohu.

Příkladem komplexnější regresivní analýzy je využití v lékařství či pojišťovnictví. Takovým příkladem je například výpočet výše životního pojištění dle zjištěných údajů od uchazeče o pojištění na základě přechozích dat od jiných klientů (informace zda je kuřák, rodinná anamnéza, povolání, a mnohé další..)

*Přejít k více formálnější definici*

##### Dělení regresivních modelů
Podle počtu nezávisle proměnných rozlišujeme modely jednoduché regrese a vícenásobné regrese. Jednoduchá regrese popisuje závislost vysvětlované proměnné na jednom regresoru. Naproti tomu vícenásobná regrese řeší situaci, kde závisle proměnná závisí na více než jednom regresoru.

#### Lineární regrese 
##### Příklad
Pearsonův korelačního koeficient
* nabývá hodnoty 0 – 1 pro kladnou korelaci, 0 – (-1) pro
zápornou korelaci
* hodnota 0 znamená, že mezi posuzovanými veličinami není žádný lineární vztah (může být nelineární) nebo tento vztah zůstal na základě dat, které máme k dispozici, neprokázán
* hodnota 1 nebo (-1) indikuje funkční závislost (lineární)