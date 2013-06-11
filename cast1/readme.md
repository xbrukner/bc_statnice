## Teoretické základy informatiky a matematika

Spousta odkazů je na stránku věnující se vypracovaným otázkám na [dqd.cz](http://statnice.dqd.cz/home:inf). Protože jsou ty otázky vypracovány na starší verzi státnic, doplnil jsem odkazy i na předměty, kterých se to týkalo, a i na další zdroje.

### 1. Množiny, relace, zobrazení, čísla.

*Základní množinové operace, množinový kalkul, potenční množina, kartézský součin. Relace a jejich vlastnosti - ekvivalence a rozklady, uspořádání a uspořádané množiny. Skládání relací, zobrazení (injekce, surjekce, bijekce). Elementární teorie čísel (dělitelnost, Euklidův algoritmus, modulární operace).*

[Úvod do informatiky](https://is.muni.cz/auth/predmety/predmet.pl?id=585042), [Základy matematiky](https://is.muni.cz/auth/predmety/predmet.pl?id=585079) ([web](http://www.math.muni.cz/~klima/ZakladyM/zakladym-fi-10.html))

[Vypracovaná část otázky na dqd.cz](http://statnice.dqd.cz/home:inf:ap1) - chybí zde teorie čísel, její části na Wikipedii: [Dělitelnost](http://cs.wikipedia.org/wiki/Dělitelnost), [Euklidův algoritmus](http://cs.wikipedia.org/wiki/Eukleidův_algoritmus), [Modulární aritmetika](http://cs.wikipedia.org/wiki/Modulární_aritmetika).

### 2. Logika

*Výroková logika, operace, syntax. Sémantika, pravdivost, splnitelnost. Dokazatelnost, důkazové metody a systémy. Normální formy (konjunktivní a disjunktivní).*

[Úvod do logiky](https://is.muni.cz/auth/predmety/predmet.pl?id=688204) ([web](http://www.fi.muni.cz/~popel/lectures/bak_logika/))

[Vypracované otázka na dqd.cz](http://statnice.dqd.cz/home:inf:ap4). (TODO - najít někde více k dokazatelnosti a důkazovým systémům?). [Důkazy programů na dqd.cz](http://statnice.dqd.cz/home:inf:ap5).

__K normálním formám:__ Hezká [animace](https://is.muni.cz/auth/th/173318/fi_b/5726674/5726798/2-29.htm) umožňující dobré pochopení, jak tyto formy fungují. Disjunktivní normální forma (DNF) je disjunkcí (or) všech ohodnocení (výjadřené vždy jako konjunkce proměnných či jejich negací), pro které je formule splněná; konjuktivní normální forma (KNF) je konjunkcí (and) všech *negací ohodnocení* (vyjádřené jako disjunkce proměnných či jejich negací), pro které formule splněná není. Aby bylo možné tuto formu vytvořit, je potřeba aby alespoň jedno ohodnocení formuli splnilo (pro DNF) či nesplnilo (KNF). Důsledkem je, že tautologii nelze vyjádřit v KNF a kontradikci v DNF.

### 3. Lineární algebra a geometrie

*Operace s vektory a maticemi, vlastnosti lineárních operací a skalárního součinu, řešení systému lineárních rovnic, determinant, vlastní čísla a vektory, inverzní matice, podprostory, báze. Analytická geometrie, afinní objekty, afinní transformace.*

[Lineární algebra](https://is.muni.cz/auth/predmety/predmet.pl?id=585386) ([web](http://www.math.muni.cz/~cadek/index.html)); afinní transformace a analytická geometrie též mimo.

K maticím - základní informace na webu [Matematika polopatě](http://www.matweb.cz/matice) (dále zde i [determinant](http://www.matweb.cz/determinanty) a [inverzní matice](http://www.matweb.cz/inverzni-matice)). Od doc. Čadka [slidy k vektorovým podprostorům, lineární nezávislosti, bázím, dimenzím a souřadnicím](http://www.math.muni.cz/~cadek/LA/pre.pdf), případně osnova jeho předmětu [Lineární algebra a geometrie](https://is.muni.cz/elearning/warp.pl?fakulta=1431;obdobi=4663;predmet=501847;qurl=%2Fel%2F1431%2Fpodzim2009%2FM1111%2Findex.qwarp;rozbalit_vse=1;prejit=).

K afinním transformacím - hezky zpracovaná stránka na [wikiknihách](http://cs.wikibooks.org/wiki/Geometrie/Afinní_transformace_souřadnic), a slidy ke [Transformacím v rovině](http://www.fi.muni.cz/~xpelanek/IV122/slidy/lingebra.pdf) z předmětu IV122 (první část slidů).

**Update 11. 6.:**
Jako dobré materiály se jeví sbírka příkladů s vysvětlením od [doc. Čadka k lineární algebře](https://is.muni.cz/el/1431/podzim2009/M1111/um/ulohy/la1_sbirka.pdf?fakulta=1431;obdobi=4663;predmet=501847), kde je vysvětlena většina věcí, a to jak s vysvětlujícími příklady, tak s příklady k procvičení (s řešením na konci). Některé věci zde vysvětleny však nejsou (vlastní čísla), na to jsou zde [slidy k předmětu Lineární modely](https://is.muni.cz/el/1433/jaro2013/MB101/um/39028946/).

### 4. Matematická analýza

*Vlastnosti reálných funkcí, polynomy, spojité funkce a limity, derivace, neurčitý a určitý integrál. Funkce více proměnných, parciální derivace.*

[Matematická analýza 1](https://is.muni.cz/auth/predmety/predmet.pl?id=585078), [2](https://is.muni.cz/auth/predmety/predmet.pl?id=632858); [Algebra?](https://is.muni.cz/auth/predmety/predmet.pl?id=632504) ([web](http://www.math.muni.cz/~polak/algebra-I.html))

Obecně k funkcím, polynomům, limitám, derivacím - [Diferenciální počet funkcí jedné proměnné](https://www.math.muni.cz/~xchudoba/matalyza.pdf), pouze k integrálům [Integrální počet funkcí jedné proměnné](http://homel.vsb.cz/~s1a64/cd/pdf/print/ip.pdf). Pro ty více aktivnější je zde [sbírka řešených příkladů příkladů z matematické analýzy I](http://is.muni.cz/do/sci/UMS/el/analyza/index.html).

Více proměnných - [differenciální počet](https://www.math.muni.cz/~plch/mapm/index_cd.html), [integrální počet](https://www.math.muni.cz/~plch/main/maple/sbirka/sbirka.html), [obojí od konkurence z VUT včetně obrázků](http://temp3120.kx.cz/m2/dif.pdf).

### 5. Grafy

*Typy grafů, stromy, stupně vrcholů, orientované grafy, komponenty souvislosti. Grafové algoritmy: prohledávání do hloubky a do šířky, hledání nejkratší cesty, minimální kostra grafu.*

[Základy matematiky](https://is.muni.cz/auth/predmety/predmet.pl?id=585079) ([web](http://www.math.muni.cz/~klima/ZakladyM/zakladym-fi-10.html)), [Nával 1](https://is.muni.cz/auth/predmety/predmet.pl?id=585358)

Základní popis grafů od [prof. Rosicekého](https://www.math.muni.cz/~rosicky/lectures/zm.pdf).
Grafové algoritmy na [dqd.cz](http://statnice.dqd.cz/home:inf:ap17) (jsou zde i další algoritmy nepokryté touto otázkou), případně slidy od [Škarvady](http://www.fi.muni.cz/~libor/vyuka/IB002/stud-materialy/sl.pdf) (od slidu 116, nutné otočit vlevo).

### 6. Formální jazyky

*Hierarchie jazyků, regulární jazyky, bezkontextové jazyky, uzávěrové vlastnosti jazyků. Reprezentace jazyků (gramatiky, regulární výrazy, automaty), převody mezi jednotlivými reprezentacemi.*

[Formální jazyky a automaty](https://is.muni.cz/auth/predmety/predmet.pl?id=585359) ([web](http://www.fi.muni.cz/usr/kretinsky/fja1.html))

Vypracování otázky na dqd.cz - [Regulární jazyky](http://statnice.dqd.cz/home:inf:ap8), [Bezkontextové jazyky](http://statnice.dqd.cz/home:inf:ap10), [Vyčíslitelnost](http://statnice.dqd.cz/home:inf:in13). Skripta k [Formálním jazykům a automatům](http://is.muni.cz/elportal/estud/fi/js06/ib005/Formalni_jazyky_a_automaty_I.pdf), IMHO hezky zpracované [slidy z MFF](http://kti.mff.cuni.cz/~bartak/automaty/index.html).

### 7. Automaty a vyčíslitelnost

*Konečný automat, zásobníkový automat, Turingův stroj. Varianty automatů, metody akceptování. Nedeterminismus, determinizace automatů. Nerozhodnutelnost, Churchova teze, diagonalizace, rekurzivně spočetné množiny, první Riceova věta.*

[Formální jazyky a automaty](https://is.muni.cz/auth/predmety/predmet.pl?id=585359) ([web](http://www.fi.muni.cz/usr/kretinsky/fja1.html)), [Vyčíslitelnost a složitost](https://is.muni.cz/auth/predmety/predmet.pl?id=632473) ([web](http://www.fi.muni.cz/usr/brim/ib107.html))

dqd.cz - [Konečné automaty](http://statnice.dqd.cz/home:inf:ap8), [Zásobníkové automaty](http://statnice.dqd.cz/home:inf:ap10), [Vyčíslitelnost](http://statnice.dqd.cz/home:inf:in13). Část zdroje k otázce 6 (především k automatům). Druhá část otázky je pak pokryta ve slidech k [Vyčíslitelnosti a složitosti](http://www.fi.muni.cz/usr/brim/ib107.html) (slidy jsou dostupné jen z domény .muni.cz, takže ssh na aisu, stáhnout tam a pak stáhnout domů :-)).

### 8. Korektnost a složitost

*Parciální a totální korektnost, důkazy korektnosti, asymptotická složitost, O-notace. Analýza korektnosti a složitosti základních algoritmů (např. řadicí algoritmy, binární vyhledávání). Třídy P, NP, PSPACE a vztahy mezi nimi, příklady problémů z jednotlivých tříd. Princip redukce problémů, NP-úplné úlohy.*

[Vyčíslitelnost a složitost](https://is.muni.cz/auth/predmety/predmet.pl?id=632473) ([web](http://www.fi.muni.cz/usr/brim/ib107.html)), [Nával 2](https://is.muni.cz/auth/predmety/predmet.pl?id=632840) 

Vypracovaná otázka [ke složitosti](http://statnice.dqd.cz/home:inf:in14), dále zdroje otázky 7, případně je část pokryta ve slidech z návalu 2.

### 9. Datové struktury

*Základní abstraktní datové struktury, podporované operace (seznam, množina, zásobník, fronta, prioritní fronta). Typické implementace (zřetězený seznam, binární vyhledávací strom, halda, hašovací tabulka). Složitost operací.*

[Nával 1](https://is.muni.cz/auth/predmety/predmet.pl?id=585358), [Nával 2](https://is.muni.cz/auth/predmety/predmet.pl?id=632840) 

Vypracovaná otázka [k datovým strukturám](http://statnice.dqd.cz/home:inf:ap15), slidy [k návalu 1](http://www.fi.muni.cz/~libor/vyuka/IB002/stud-materialy/sl.pdf).
### 10. Algoritmy

*Řadicí algoritmy, algoritmy pro práci s řetězci. Příklady rekurzivních algoritmů, výhody a nevýhody rekurze, odstranění rekurze. Metody konstrukce efektivních algoritmů (rozděl a panuj, dynamické programování, hladové algoritmy), příklady algoritmů.*

[Nával 1](https://is.muni.cz/auth/predmety/predmet.pl?id=585358), [Nával 2](https://is.muni.cz/auth/predmety/predmet.pl?id=632840) 

Vypracované otázky - [řadící algoritmy](http://statnice.dqd.cz/home:inf:ap16), [práce s řetězci](http://statnice.dqd.cz/home:inf:in17), [rekurze](http://statnice.dqd.cz/home:inf:ap6), [efektivní algoritmy](http://statnice.dqd.cz/home:inf:in19).

### 11. Paradigmata programovacích jazyků

*Imperativní programování. Funkcionální paradigma (základní princip, redukční krok, redukční strategie a jejich vlastnosti, skládání funkcí, funkce vyššího řádu, příklady).*

[Principy programovacích jazyků](https://is.muni.cz/auth/predmety/predmet.pl?id=632538), [Funkcionální programování](https://is.muni.cz/auth/predmety/predmet.pl?id=585044)

Vypracované otázky - [vyhodnocování výrazů (redukční strategie)](http://statnice.dqd.cz/home:inf:ap7), [rekurze](http://statnice.dqd.cz/home:inf:ap7). TODO - něco k imperativnímu programování.
