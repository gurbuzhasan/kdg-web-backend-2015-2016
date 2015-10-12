# KdG: Web Backend (2015-2016)

docent: Pascal Nosenzo (pascal.nosenzo@kdg.be)

ECTS: [Web back-end WP 2](https://bamaflexweb.kdg.be/BMFUIDetailxOLOD.aspx?a=56428&b=1&c=1)

## Deadlines


- Deadline 02
	- Deadline: voor de les van woensdag 14 oktober 2015
	- Opdracht: tot en met opdracht POST (herhalingsopdracht hoeft niet) (slide 94)
	- Vergeet niet een commit van je opdrachten te doen
	- Neem de slides/voorbeelden tot en met sessions/cookies eens door, daar gaan we mee verder volgende les.

- Deadline 01
	- Deadline: voor de les van woensdag 7 oktober 2015
	- Opdracht: tot en met opdracht functions-recursive (slide 85)
	- Vergeet niet een commit van je opdrachten te doen
	- Neem de slides/voorbeelden van $_GET/$_POST eens door, daar gaan we mee verder volgende les.

## Cursus

De cursus vind je terug op de [Web Backend GitHub repository](https://github.com/pascalculator/web-backend). In de [README.md](https://github.com/pascalculator/web-backend/blob/master/README.md) vind je instructies terug over hoe je deze cursus moet installeren.

### Stappenplan voor de installatie:

1. Git 

	- [Git](https://git-scm.com/downloads) installeren

		- zeker toevoegen aan de PATH variabele

	- [Github](https://github.com/) account aanmaken

2. Cursus web backend structuur

	- de volgende mappenstructuur aanmaken

		```
		web-backend
			|- cursus (NOG NIET AANMAKEN -> dit gebeurt via Git)
			|- oplossingen
		```

	- Op Github een repository "web-backend-oplossingen" aanmaken en deze linken aan je oplossingen map. Bekijk [de instructies](https://github.com/pascalculator/web-backend#je-eigen-oplossingen-uploaden-naar-je-online-repository).

	- De [cursus via Git binnenhalen](https://github.com/pascalculator/web-backend#git-gebruiken-om-cursus-te-downloaden)

		- Let op: de map "cursus" wordt automatisch aangemaakt met dit commando: ```git clone https://github.com/pascalculator/web-backend.git cursus``` (let op het laatste woordje __cursus__. Dat is de naam van de map die aangemaakt zal worden.)

3. Virtual hosts instellen

	- [Instructies](https://github.com/pascalculator/web-backend/raw/master/public/cursus/virtual-server-setup.pdf)

	- Voorbeeld van een [virtual host configuratie](https://raw.githubusercontent.com/pascalculator/web-backend/master/public/cursus/vhost-voorbeeld.txt)

		- Deze virtual host config kan je integraal overnemen (mits de nodige aanpassingen), op voorwaarde dat je de laatste nieuwe versie van XAMPP (Apache) hebt draaien

		- Mensen met Mac: lees bijgevoegde commentaar

	- Stel je virtual hosts zo in dat wanneer je naar 

		- http://web-backend.local surft de lokale map /web-backend/cursus/public wordt ingeladen

		- http://oplossingen.web-backend.local surft de lokale map /web-backend/oplossingen wordt ingeladen

4. Je naam, email en url van GitHub account toevoegen aan dit bestand

	- Edit dit bestand door op het potloodje te klikken

	- Voeg je gegevens toe

	- Voer een [pull request](https://help.github.com/articles/using-pull-requests/) uit om de wijzigingen tot bij mij te krijgen
	
## Spelregels

- Deze cursus is zelfstudie: je doorloopt de slides, bekijkt de overeenstemmende voorbeelden en maakt vervolgens de opdrachten. Dat betekent niet dat je niet mag overleggen of vragen mag stellen. De docent is er om je te begeleiden en feedback te geven. Maak hier dus gebruik van!

- Je bent aanwezig tijdens de lessen zodat er persoonlijke begeleiding kan gegeven worden. Afwezigheden worden aan mij gemeld via mail én op de KdG-voorgestelde manier gemeld (via e-student services)

- Je gemaakte opdrachten komen op je publieke GitHub repository.

- Per gemaakte opdracht voer je minstens één commit uit, zodat het duidelijk is wanneer je aan welke oefening hebt gewerkt. 

- Deadlines worden gerespecteerd, zonder discussie.

- Je mag kleine dingen kopiëren of je door de voorbeeldopdrachten laten inspireren als je vast zit op voorwaarde dat je elke lijn code kan uitleggen. Integraal een oefening kopiëren en wat variabelen veranderen of commentaar bijschrijven, staat uiteraard gelijk aan plagiaat.

- Vroeger doorgaan tijdens de lessen is geen enkel probleem, mits je dit bij het begin van de les laat weten en je tijdens je aanwezigheid hebt laten zien waar je aan gewerkt hebt.

- Heb je foutjes gevonden of klopt er iets niet? Aanpassingen/verbeteringen (pull requests) aan de cursus worden beloond met minstens één extra punt op het eindtotaal én een eerbare vermelding op de [contributors](https://github.com/pascalculator/web-backend#contributors)-lijst van de cursus.

- Bij problemen (te hoge werkdruk, planning, ...) kan je mij dit in vertrouwen laten weten en dan zoeken we samen naar een oplossing. Het is belangrijk dat je dit -op voorhand- laat weten en niet bv. nadat een deadline is verstreken.

## Beoordeling

- Permanente evaluatie tijdens de lessen op basis van de opdrachten en betrokkenheid
	- Laat je zien dat je jezelf kan bijsturen?
	- Ben je kritisch ten opzichte van de oplossingen?
	- Ben je periodiek met de oefeningen bezig?
	- Verricht je opzoekingswerk?
	- Stel je voldoende vragen?
	- Haal je de deadlines of communiceer je tijdig wanneer dit niet lukt?
	- Deze evaluatie kan je ook altijd even komen raadplegen
	- 50% van het eindtotaal

- Resultaat van de tussentijdse opdrachten
	- Op het einde van elke periode volgt er een opdracht om te kijken wat je huidige kennis is. Deze wordt beoordeeld op:
		- Werkbaarheid
		- Gebruikte technieken comform met de cursus
		- Cleane code (indents, herbruikbaarheid: functies/classes, scheiding logica & html)
	- Deze opdracht moet individueel opgelost worden. Plagiaat/kopiëren wordt zwaar bestraft en krijgen een glansloze vermelding in de "Hall of shame".
	- 50% van het eindtotaal

Er wordt geen eindexamen voor Web Backend geörganiseerd.

## Feedback ivm cursus

Graag! Je mag mij altijd aanspreken tijdens de les of een mailtje sturen met eventuele verbeteringen ivm de cursus.

## Studenten

1. Alex Vanderbist
	- email: alex.vanderbist@gmail.com
	- GitHub: https://github.com/AlexVanderbist/

2. Siebe Vandeneynde
	- email: siebe.vandeneynden@student.kdg.be
	- GitHub: https://github.com/SiebeVE/

3. Lander Verschueren
	- email: lander.verschueren@student.kdg.be
	- GitHub: https://github.com/LanderVerschueren

4. Wouter Schoofs
	- email: schoofs.wouter@gmail.com
	- GitHub: https://github.com/WouterSchoofs/

5. Nick Verstocken
	- email: verstockennick@gmail.com
	- GitHub: https://github.com/nickverstocken/

6. Ruben De Swaef
	- email: rubendeswaef@gmail.com
	- GitHub: https://github.com/rubends/

7. Dieter Vercammen
	- email: dieter.vercammen@student.kdg.be
	- GitHub: https://github.com/DieterVercammen/

8. Joren VH
	- email: joren.vh@hotmail.com
	- GitHub: https://github.com/jorenvh1/

9. Luka Verhoeven
	- email: lka.v.lv@gmail.com
	- GitHub: https://github.com/LukaVerhoeven/

10. Patokin Anton
	- email: Patokin.anton@gmail.com
	- GitHub: https://github.com/Anton-Patokin/


11. Sander Peeters
	- email: sander.peeters@student.kdg.be
	- GitHub: https://github.com/SanderPeeters/

12. Kevin Bavuidi
	- email: kevin.bavuidi@hotmail.com
	- GitHub: https://github.com/lekevinbm/


13. Cedric Proost
	- email: proost_cedric@hotmail.com
	- GitHub: https://github.com/davidcassedie/

14. Stig Vanbrabant
	- email: stig.vanbrabant@student.kdg.be
	- GitHub: https://github.com/StigVanbrabant/

15. Phedra Moerloos
	- email: phedra.moerloos@student.kdg.be
	- GitHub: https://github.com/PhedraMoerloos/

16. Sarah Jehin
	- email: sarah.jehin@student.kdg.be
	- GitHub: https://github.com/SarahJehin/

17. Denis Inghelbrecht
	- email: denis.inghelbrecht@student.kdg.be
	- GitHub: https://github.com/YKdenis/

18. Edward Vereertbrughen
	- email: Edward.Vereertbrugghen@gmail.com
	- GitHub: https://github.com/edwwaarrdd/

19. Toon De Jonge
	- email: toon.dejonge@student.kdg.be
	- GitHub: https://github.com/DeJongeToon/

20. Felix Rijkers
	- email: felix.rijkers@student.kdg.be
	- GitHub: https://github.com/FelixRijkers/

21. Noemi Belloy
	- email: noemi.belloy@student.kdg.be
	- GitHub: https://github.com/NoemiBelloy/

22. Rowan van Ekeren
	- email: rowan.vanekeren@student.kdg.be
	- GitHub: https://github.com/rowanvanekeren/

23. Dries Heyninck
	- email: dries.heyninck@gmail.com
	- GitHub: https://github.com/DriesH/

24. Ruben Van Ostaeyen
	- email: rubenvanostaeyen@hotmail.com
	- GitHub: https://github.com/RubenVO/

25. Adriaan Marain
	- email: adriaanmarain300@gmail.com
	- GitHub: https://github.com/AdrianMrn/

26. Sam De Wachter
	- email: sam.dewachter@student.kdg.be
	- GitHub: https://github.com/samdewachter/

27. Seppe Renty
	- email: seppe.renty@student.kdg.be
	- GitHub: https://github.com/sepperenty/

28. Sharon Meeus
	- email: sharon.meeus@gmail.com
	- GitHub: https://github.com/SharonMeeus/

29. Seppe Goossens
	- email: goossens.seppe@hotmail.com
	- GitHub: https://github.com/SeppeDev/

30. Sacha De Pauw
	- email: sacharypens@gmail.com
	- GitHub: https://github.com/sacharypens/

31. Ben Vaes
	- email: ben.vaes@student.kdg.be
	- GitHub: https://github.com/BenVaes/

32. Sophie Moons
	- email: sophie.moons@student.kdg.be
	- GitHub: https://github.com/SophieMoons/