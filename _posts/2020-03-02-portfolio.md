---
title: "Portfolio"
date: 2020-03-11T10:24:30-04:00
categories:
  - Portfolio
tags:
  - Portfolio
  - Projekt
  - Utveckling
---

Här följer en kort sammanfattning av några projekt jag har arbetat med, antingen under utbildningen eller på fritiden.
Jag ska försöka hålla den här listan så koncis som möjligt så att man snabbt kan få en uppfattning om vad jag har gjort.

## Autonom bil
![Nucleo Wagon](/assets/images/posts/portfolio/nucleo_wagon.jpg)

Byggde ihop en självkörande bil baserat på en [Nucleo F103RB](https://www.st.com/en/evaluation-tools/nucleo-f103rb.html) och [FreeRTOS](https://www.freertos.org/). Med hjälp av en ultraljudssensor monterad på en servomotor så kan den skanna av sin omgivning och upptäcka eventuella hinder. Den kan navigera sig igenom en hinderbana utan att fastna och tar sig även ur hörn på egen hand. Det finns också en gripklo monterad som styrs med hjälp av en [solenoid](https://sv.wikipedia.org/wiki/Solenoid) för avskräckande syfte. Koden är skriven i C++.

Nedan följer ett litet filmklipp på bilen "in action"! Det är tyvärr inte det bästa klippet, men samtidigt det ända klippet jag har på bilen. Notera också den spännande musiken (finns mest för att dölja det oljud som motorerna gav ifrån sig).

<iframe width="560" height="315" src="https://www.youtube.com/embed/JJ5EMQD3vvE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## GuardAlarm
![GuardAlarm](/assets/images/posts/portfolio/guardAlarm.jpg)

Ett projekt där jag konstruerade ett "hemlarm" baserat på en [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3). Till det har jag också skrivit ett tillhörande program i C++ som körs på en vanlig dator. Datorn, tillsammans med mitt program, agerar "larmcentral" och kommunicerar ständigt med Arduinon. Förutom de grundläggande funktionerna som att kunna larma av/på, utlösa larmet med mera, följer nu en punktlista på spännande funktionalitet som finns med:

* Möjlighet att aktivera hela larmet eller bara ett "skallarm".
* Loggning av alla händelser, komplett med tidsstämpel, ev. användar-ID och beskrivning av händelse.
* Lägga till fler användare enkelt genom att ändra i en text-fil.
* Verifiering av PIN-kod och användare mot "larmcentralens" databas.
* Avlarma med en speciell "nödkod" för att signalera nödsituation till larmcentralen.
* LED, och ljud-feedback för att indikera systemets status vid olika lägen.

Detta är bara en översiktlig beskrivning av de funktioner som finns.

## ESP8266 och Snake
![Snake på en Lolin D1 mini](/assets/images/posts/portfolio/snake.jpg)

I det här projektet ville jag lära mig mer om hur det är att jobba med en display. Jag bestämde mig att för att genomföra detta genom att programmera det klassiska spelet [Snake](https://sv.wikipedia.org/wiki/Snake).
Jag använde följande komponenter:

* [Lolin D1 mini (baserad på ESP8266)](https://docs.wemos.cc/en/latest/d1/d1_mini.html)
* TFT 1.4 Shield

Sedan finns det också 2 knappar för att styra programmet. Med hjälp av knapparna styr du ormen och försöker äta så mycket frukt som möjligt för att få en så hög "highscore" som du kan. Varje gång som du äter en frukt så blir ormen längre och en ny frukt placeras ut slumpmässigt på spelplanen. Råkar du köra in i "väggen" eller i din svans så är spelet över.

I klippet nedan kan du se spelet i rörelse.

<iframe width="560" height="315" src="https://www.youtube.com/embed/CheBJJ8W5WQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Det finns många fler roliga projekt att prata om och jag ska försöka uppdatera det här inlägget allt eftersom. Jag hoppas du har fått en lite bättre uppfattning om vad jag har gjort och att du tycker det låter intressant!

Har du några frågor så går det bra att maila mig!

--
*Detta inlägg kommer uppdateras löpande med fler projekt*
