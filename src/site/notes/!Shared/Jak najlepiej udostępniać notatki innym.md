---
{"dg-publish":true,"permalink":"/shared/jak-najlepiej-udostepniac-notatki-innym/","dgHomeLink":false,"dgPassFrontmatter":false}
---

# Jak najlepiej udostępniać notatki innym
## Intencja :fas_star:
- Udostępnianie notatki powinno być:
	- Jak najszybsze
	- Bezproblemowe - powinno zawsze działać
	- Spełniać moje use-cases

> [!Warning]
> - Temat na odwykg! 
## Use-cases
- Chce móc udostępnić notatkę dotyczącą jakiegoś tematu, np. notatki ze spotkania
- Często jedna notatka jest powiązana z inną, więc chce aby w łatwy sposób ta powiązana notatka również została udostępniona
- Nie chce tworzyć jakiejś dodatkowej notatki ala home page
- Chce móc łatwo wysłać link do tej jednej, konkretnej notatki
- Udostępniona notatka powinna być jak najbardziej spójna z tym jak mi się renderuje w Obsidianie
- Wolałbym za tą integrację nie płacić
## Rozwiązania do sprawdzenia
- Digital-garden : https://github.com/oleeskild/obsidian-digital-garden
	- Notatki inkludowane nie mają z automatu wyświetlanej swojej nazwy pliku
		- Rozwiązaniem jest filename heading sync albo dodawanie |nazwa po linku do notatki
	- Duża wielkość czcionek...
		- Łatwo sterować CSSem wyglądem opublikowanych notatek
	- Transclusion odnoszące się tylko do części notki inkludują jej całość :/
- MindStone : https://github.com/TuanManhCao/digital-garden
	- Wszystkie attachmenty muszą być w jednym folderze
		- [[Jak łatwo kopiować attachmenty powiązane z notką|Jak łatwo kopiować attachmenty powiązane z notką]]
	- Nie działają transclusions!!!
- Publish to git : przestało mi działać...
- Obsidian to Notion : https://github.com/EasyChris/obsidian-to-notion
- Obsidian Publish - ~80 zł/msc 
- Obsidian zola - https://github.com/ppeetteerrs/obsidian-zola

> [!Idea] Synchronizacja folderu z udostępnionymi notatkami do repozytorium git
> Na podstawie tego repozytorium zbudowanie strony, integracji.
>> [!Tip] Path Finder, ChronoSync Express on setapp


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>


> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast|Spire Blast]]
## Lista proponowanych testów
- W pierwszym biomie dać szybciej choke point? ^fc5f29
	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast|Spire Blast]]
## Intencja :fas_star:
- Stworzyć osobny zoneList aby
	- Przetestować 
		- Trzy pierwsze biomy
			- Najtrudniejsze plansze?
		- Flytrapa
			- Czy ten zasięg też tak ludzi będzie wkurzać?
				- To że raz łapie, raz nie, że to działa losowo

## Design
- Na jaki czas playthrough celujemy? 
	- 45 min - to wydaje się spoko, bo po 30 minutach już gracz się zmęczy i można to wykorzystać, ale też bez przesady
		- Na to potrzebujemy 20-30 plansz. Tyle można założyć, że każdy gracz dojdzie
			- 20 dojdą wszyscy
			- 30 dojdzie część
			- +30 dojdą nieliczni
- Chcemy uwzględnić takie momenty w grze:
	- [[Pierwszy choke point|Pierwszy choke point]]
	- [[Onboarding pet ability|Onboarding pet ability]]
		- L16
	- [[onboarding flytrap|onboarding flytrap]]
	- [[onboarding two lives|onboarding two lives]]
		- L16
		- mechanika która nie ma objectiva
- Czego myślę żeby nie uwzględniać:
	- Challenge biome

> [!Hint] Długo się gra rozkręca
> W połowie testu dla większości wprowadzamy pierwszego choke pointa

^b9c52e

> [!Tip] Onboarding bomby jest na planszy z 2lives
> Może warto zrobić alternatywne plansze onboardingowe mechanik?
> Inne onboardingi z tym problemem:
> - Na [[color changing blocks|color changing blocks]] jest onboarding z side-towers i bombami

^8fdcb2

> [!Question] Czy chcemy zachować kolejność wprowadzania mechanik w RC?
> Czy w tym buildzie chcemy zachować kolejność wprowadzania mechanik z RC?
````col
```col-md
==ZA==
- Lepiej zmieniać jak najmniej rzeczy (KISS)
```
```col-md
==PRZECIW== 
- Dla testowania flytrapa lepiej wprowadzić wcześniej swap color niż bomby
```
````

> [!Question] Które jeszcze mechaniki chcemy przetestować?
> - Laser blocks?
> - Coś bliżej...
> 	- Shoot deflector?
> 	- ==Side shooter==
## Stan ukończenia
- Pozaznaczałem 40 plansz które są kandydatami dobrymi do tego builda
	- Te plansze poukładałem w sensownej kolejności
### To-Do
- Popatrzeć na to jeszcze raz dokładniej
	- Popatrzeć jak jest poukładany poziom trudności kolejnych etapów tego builda
		- Przez etap rozumiem: 
			- nowa mechanika i plansze z nową mechaniką, 
				- etap kończy się wraz z planszą z kolejną nową mechaniką


</div></div>

	- Duży impact na retencję dla nowych graczy
- Uprościć onboardingi:
	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast|Spire Blast]]
## Intencja :fas_star:
- Stworzyć osobny zoneList aby
	- Przetestować 
		- Trzy pierwsze biomy
			- Najtrudniejsze plansze?
		- Flytrapa
			- Czy ten zasięg też tak ludzi będzie wkurzać?
				- To że raz łapie, raz nie, że to działa losowo

## Design
- Na jaki czas playthrough celujemy? 
	- 45 min - to wydaje się spoko, bo po 30 minutach już gracz się zmęczy i można to wykorzystać, ale też bez przesady
		- Na to potrzebujemy 20-30 plansz. Tyle można założyć, że każdy gracz dojdzie
			- 20 dojdą wszyscy
			- 30 dojdzie część
			- +30 dojdą nieliczni
- Chcemy uwzględnić takie momenty w grze:
	- [[Pierwszy choke point]]
	- [[Onboarding pet ability]]
		- L16
	- [[onboarding flytrap]]
	- [[onboarding two lives]]
		- L16
		- mechanika która nie ma objectiva
- Czego myślę żeby nie uwzględniać:
	- Challenge biome

> [!Hint] Długo się gra rozkręca
> W połowie testu dla większości wprowadzamy pierwszego choke pointa

^b9c52e

> [!Tip] Onboarding bomby jest na planszy z 2lives
> Może warto zrobić alternatywne plansze onboardingowe mechanik?
> Inne onboardingi z tym problemem:
> - Na [[color changing blocks]] jest onboarding z side-towers i bombami

^8fdcb2

> [!Question] Czy chcemy zachować kolejność wprowadzania mechanik w RC?
> Czy w tym buildzie chcemy zachować kolejność wprowadzania mechanik z RC?
````col
```col-md
==ZA==
- Lepiej zmieniać jak najmniej rzeczy (KISS)
```
```col-md
==PRZECIW== 
- Dla testowania flytrapa lepiej wprowadzić wcześniej swap color niż bomby
```
````

> [!Question] Które jeszcze mechaniki chcemy przetestować?
> - Laser blocks?
> - Coś bliżej...
> 	- Shoot deflector?
> 	- ==Side shooter==
## Stan ukończenia
- Pozaznaczałem 40 plansz które są kandydatami dobrymi do tego builda
	- Te plansze poukładałem w sensownej kolejności
### To-Do
- Popatrzeć na to jeszcze raz dokładniej
	- Popatrzeć jak jest poukładany poziom trudności kolejnych etapów tego builda
		- Przez etap rozumiem: 
			- nowa mechanika i plansze z nową mechaniką, 
				- etap kończy się wraz z planszą z kolejną nową mechaniką


</div></div>

	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

- Ilości mechanik

</div></div>

- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast]]
## Intencja :fas_star:
- Jakie mamy globalne parametry balansowe?

## Przypływ / odpływ coinsów

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">

# Za wysokie ceny boosterów


</div>

> [!INFO]+
> groups: [[notes|notes]] | [[topic notes|topic notes]]
> context: [[c: Spire Blast|c: Spire Blast]]
> tags: 

[[balance table|balance table]]: https://docs.google.com/spreadsheets/d/15mUeCzOH_56SoNmTqo3z31lymndgcVpQISLAXwDMH-g/edit?usp=sharing  

Według Economy stats na [[notion|notion]] coins per level gracz zdobywa średnio 170.

# Rozwiązanie:
- Nie chcę zmieniać, bo tak naprawdę to z feedbacku nie widać, żeby te ceny były za wysokie. Feedback ([[Feedback session 31-08-21#ceny powerup upgrades są za wysokie są za wysokie|Feedback session 31-08-21#ceny powerup upgrades są za wysokie są za wysokie]]) dotyczył bardziej [[ceny powerup upgrades są za wysokie|ceny powerup upgrades są za wysokie]]
- W dodatku chcemy zaadresować [[Boostery są za słabe|Boostery są za słabe]] więc to zwiększy ich wartość.






</div></div>

- ==Częściej / rzadziej wypadające skrzynki==
## Przypływ / odpływ gemsów
- Tańsze / droższe skiny
## Przypływ / odpływ starsów
- ==Mniej punktów na 3 stars==
## Przypływ / odpływ skinów
- Tańsze / droższe skiny
## Tańsze stargates
- To ma duży wpływ na retencję
	- Tylko to ma wpływ na challenge




</div></div>

- ==Ciężej waląca się wieża (któryś z poniższych)==
	- Ciężej / łatwiej waląca się wieża (zmiana fizyki)
	- Zmienić ilości aktywnych segmentów na wieży
		- Zmniejszyć?
- Na planszach relax dawać nieskończoną ilość ammo...
	- Tylko to wymaga przeróbki UI, nauczenia dodatkowego?
- Zmniejszyć ilość objectivów na planszach
	- Chodziłoby o to, żeby zmniejszyć ilość różnych objectivów na planszach:
		- Przed abtestem były: cages, color changing bl., smok, transform
		- Po abteście: cages, color changing bl, smok
		- > [!Warning] Trudne w produkcji
- W pierwszym biomie onboardować mniej mechanik
	- To się wiąże z przebudową LD dużej części planszy pierwszego biomu
		- Pytanie czy mamy jakieś podstawy (z analityki) że coś z pierwszym biomem jest nie tak?
		- ==Nie jesteśmy tego w stanie zrobić w tym relase==
## Test
Test

</div></div>


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>


> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast]]
## Lista proponowanych testów
- W pierwszym biomie dać szybciej choke point? ^fc5f29
	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast]]
## Intencja :fas_star:
- Stworzyć osobny zoneList aby
	- Przetestować 
		- Trzy pierwsze biomy
			- Najtrudniejsze plansze?
		- Flytrapa
			- Czy ten zasięg też tak ludzi będzie wkurzać?
				- To że raz łapie, raz nie, że to działa losowo

## Design
- Na jaki czas playthrough celujemy? 
	- 45 min - to wydaje się spoko, bo po 30 minutach już gracz się zmęczy i można to wykorzystać, ale też bez przesady
		- Na to potrzebujemy 20-30 plansz. Tyle można założyć, że każdy gracz dojdzie
			- 20 dojdą wszyscy
			- 30 dojdzie część
			- +30 dojdą nieliczni
- Chcemy uwzględnić takie momenty w grze:
	- [[Pierwszy choke point]]
	- [[Onboarding pet ability]]
		- L16
	- [[onboarding flytrap]]
	- [[onboarding two lives]]
		- L16
		- mechanika która nie ma objectiva
- Czego myślę żeby nie uwzględniać:
	- Challenge biome

> [!Hint] Długo się gra rozkręca
> W połowie testu dla większości wprowadzamy pierwszego choke pointa

^b9c52e

> [!Tip] Onboarding bomby jest na planszy z 2lives
> Może warto zrobić alternatywne plansze onboardingowe mechanik?
> Inne onboardingi z tym problemem:
> - Na [[color changing blocks]] jest onboarding z side-towers i bombami

^8fdcb2

> [!Question] Czy chcemy zachować kolejność wprowadzania mechanik w RC?
> Czy w tym buildzie chcemy zachować kolejność wprowadzania mechanik z RC?
````col
```col-md
==ZA==
- Lepiej zmieniać jak najmniej rzeczy (KISS)
```
```col-md
==PRZECIW== 
- Dla testowania flytrapa lepiej wprowadzić wcześniej swap color niż bomby
```
````

> [!Question] Które jeszcze mechaniki chcemy przetestować?
> - Laser blocks?
> - Coś bliżej...
> 	- Shoot deflector?
> 	- ==Side shooter==
## Stan ukończenia
- Pozaznaczałem 40 plansz które są kandydatami dobrymi do tego builda
	- Te plansze poukładałem w sensownej kolejności
### To-Do
- Popatrzeć na to jeszcze raz dokładniej
	- Popatrzeć jak jest poukładany poziom trudności kolejnych etapów tego builda
		- Przez etap rozumiem: 
			- nowa mechanika i plansze z nową mechaniką, 
				- etap kończy się wraz z planszą z kolejną nową mechaniką


</div></div>

	- Duży impact na retencję dla nowych graczy
- Uprościć onboardingi:
	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast]]
## Intencja :fas_star:
- Stworzyć osobny zoneList aby
	- Przetestować 
		- Trzy pierwsze biomy
			- Najtrudniejsze plansze?
		- Flytrapa
			- Czy ten zasięg też tak ludzi będzie wkurzać?
				- To że raz łapie, raz nie, że to działa losowo

## Design
- Na jaki czas playthrough celujemy? 
	- 45 min - to wydaje się spoko, bo po 30 minutach już gracz się zmęczy i można to wykorzystać, ale też bez przesady
		- Na to potrzebujemy 20-30 plansz. Tyle można założyć, że każdy gracz dojdzie
			- 20 dojdą wszyscy
			- 30 dojdzie część
			- +30 dojdą nieliczni
- Chcemy uwzględnić takie momenty w grze:
	- [[Pierwszy choke point]]
	- [[Onboarding pet ability]]
		- L16
	- [[onboarding flytrap]]
	- [[onboarding two lives]]
		- L16
		- mechanika która nie ma objectiva
- Czego myślę żeby nie uwzględniać:
	- Challenge biome

> [!Hint] Długo się gra rozkręca
> W połowie testu dla większości wprowadzamy pierwszego choke pointa

^b9c52e

> [!Tip] Onboarding bomby jest na planszy z 2lives
> Może warto zrobić alternatywne plansze onboardingowe mechanik?
> Inne onboardingi z tym problemem:
> - Na [[color changing blocks]] jest onboarding z side-towers i bombami

^8fdcb2

> [!Question] Czy chcemy zachować kolejność wprowadzania mechanik w RC?
> Czy w tym buildzie chcemy zachować kolejność wprowadzania mechanik z RC?
````col
```col-md
==ZA==
- Lepiej zmieniać jak najmniej rzeczy (KISS)
```
```col-md
==PRZECIW== 
- Dla testowania flytrapa lepiej wprowadzić wcześniej swap color niż bomby
```
````

> [!Question] Które jeszcze mechaniki chcemy przetestować?
> - Laser blocks?
> - Coś bliżej...
> 	- Shoot deflector?
> 	- ==Side shooter==
## Stan ukończenia
- Pozaznaczałem 40 plansz które są kandydatami dobrymi do tego builda
	- Te plansze poukładałem w sensownej kolejności
### To-Do
- Popatrzeć na to jeszcze raz dokładniej
	- Popatrzeć jak jest poukładany poziom trudności kolejnych etapów tego builda
		- Przez etap rozumiem: 
			- nowa mechanika i plansze z nową mechaniką, 
				- etap kończy się wraz z planszą z kolejną nową mechaniką


</div></div>

	- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

- Ilości mechanik

</div></div>

- 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">



</div>

> [!Info]+ Spire Blast Project File
> Project Link: [[Spire Blast]]
## Intencja :fas_star:
- Jakie mamy globalne parametry balansowe?

## Przypływ / odpływ coinsów

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">

# Za wysokie ceny boosterów


</div>

> [!INFO]+
> groups: [[notes]] | [[topic notes]]
> context: [[c: Spire Blast]]
> tags: 

[[balance table]]: https://docs.google.com/spreadsheets/d/15mUeCzOH_56SoNmTqo3z31lymndgcVpQISLAXwDMH-g/edit?usp=sharing  

Według Economy stats na [[notion]] coins per level gracz zdobywa średnio 170.

# Rozwiązanie:
- Nie chcę zmieniać, bo tak naprawdę to z feedbacku nie widać, żeby te ceny były za wysokie. Feedback ([[Feedback session 31-08-21#ceny powerup upgrades są za wysokie są za wysokie]]) dotyczył bardziej [[ceny powerup upgrades są za wysokie]]
- W dodatku chcemy zaadresować [[Boostery są za słabe]] więc to zwiększy ich wartość.






</div></div>

- ==Częściej / rzadziej wypadające skrzynki==
## Przypływ / odpływ gemsów
- Tańsze / droższe skiny
## Przypływ / odpływ starsów
- ==Mniej punktów na 3 stars==
## Przypływ / odpływ skinów
- Tańsze / droższe skiny
## Tańsze stargates
- To ma duży wpływ na retencję
	- Tylko to ma wpływ na challenge




</div></div>

- ==Ciężej waląca się wieża (któryś z poniższych)==
	- Ciężej / łatwiej waląca się wieża (zmiana fizyki)
	- Zmienić ilości aktywnych segmentów na wieży
		- Zmniejszyć?
- Na planszach relax dawać nieskończoną ilość ammo...
	- Tylko to wymaga przeróbki UI, nauczenia dodatkowego?
- Zmniejszyć ilość objectivów na planszach
	- Chodziłoby o to, żeby zmniejszyć ilość różnych objectivów na planszach:
		- Przed abtestem były: cages, color changing bl., smok, transform
		- Po abteście: cages, color changing bl, smok
		- > [!Warning] Trudne w produkcji
- W pierwszym biomie onboardować mniej mechanik
	- To się wiąże z przebudową LD dużej części planszy pierwszego biomu
		- Pytanie czy mamy jakieś podstawy (z analityki) że coś z pierwszym biomem jest nie tak?
		- ==Nie jesteśmy tego w stanie zrobić w tym relase==
## Test
Test

</div></div>





