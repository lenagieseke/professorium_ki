name: inverse
layout: true
class: center, middle, inverse
---


#### Impulsvortrag 
  
# *Künstliche Intelligenz*

### Lena Gieseke


#### 30.06.2023 | Professorium


???
.task[COMMENT:]  

Ziel: besseres Verständnis, interessante Erkenntnisse, Wissen jenseits des Hypes

geht es um einen aller ersten Einblick in den Themenbereich der Künstlichen Intelligenz wie ich ihn mir auch z.B. als Einstieg für Studierende im ersten Semester vorstellen könnte.

Ich möchte ihnen heute ein Verständnis dafür vermitteln, wo wir genau

---
layout: false

# Künstliche Intelligenz

.center[<img src="img/digital_evolution.jpg" alt="digital_evolution" style="width:100%;">]

.footnote[[[Bild: promatis]](https://www.promatis.de/2019/01/18/digitale-transformation-oder-digitale-evolution/)]


???
.task[COMMENT:]  

stehen in Bezug auf Künstliche Intelligenz und ob Roboter und Algorithmen wirklich kurz davor stehen die besseren Menschen zu werden.

Im speziellen werde ich die Begrifflichkeiten

---

# Künstliche Intelligenz

* Künstliche Intelligenz, Machine Learning, Deep Learning

???
.task[COMMENT:]  

Künstliche Intelligenz, Machine Learning, Deep Learning klären, werde auf die Rolle und Eigenschaften von
--
* Daten

???
.task[COMMENT:]  

Daten eingehen und ihnen im Verlauf auch aktuelle

--
* Möglichkeiten und Begrenzungen

???
.task[COMMENT:]  

Möglichkeiten und Begrenzungen von KI aufzeigen. 

Anhand dieser Themen hoffe ich, dass sie

---
# Künstliche Intelligenz

* Künstliche Intelligenz, Machine Learning, Deep Learning
* Daten
* Möglichkeiten und Begrenzungen


???
.task[COMMENT:]  

...Überblick über relevante Begrifflichkeiten einen Überblick über relevante Begrifflichkeiten gewinnen, ein intuitives Verständnis über aktuelle Handlungsfelder entwickeln und dadurch vielleicht zu eigenen Ideen für Projekte im Themenfeld der KI motiviert werden.


Kommen wir zu grundlegenden Frage: was ist denn nun eigentlich KI?

Der Traum der ersten KI-Pioniere war es, Maschinen zu konstruieren, die die gleichen Eigenschaften wie die menschliche Intelligenz besitzen. 

Dieses Ziel nennt man starke KI oder *general AI*...

---
.header[Künstliche Intelligenz]

## Starke KI

???
.task[COMMENT:]  

--

.center[<img src="img/robots.png" alt="robots" style="width:70%;">]  .footnote[[Bild: Growth Mantra](https://www.growthmantra.com.au/thinking/)]


???
.task[COMMENT:]  

Also *fabelhafte Maschinen* die alle unsere Sinne und unseren Verstand haben und denken wie wir.

--

Starken KI-Maschinen sind nachwievor Science Fiction!

???
.task[COMMENT:]  

Aber von solcher allgemeingültiger Intelligenz sind wir nach wie vor sehr weit entfernt.


Die tatsächlich aktuell verfügbaren Möglichkeiten fallen unter den Begriff der

---
.header[Künstliche Intelligenz]

## Schwache KI


???
.task[COMMENT:]  

schwachen KI, was bedeutet, dass ganz...

--

Bestimmte Aufgaben werden genauso gut oder besser als von Menschen erledigt.


???
.task[COMMENT:]  

...bestimmte Aufgaben in einem eingeschränkten Themenbereich genauso gut oder besser als von Menschen erledigt werden.

Hier ist es die sehr wichtige Unterscheidung zur menschlichen Intelligenz, dass es aktuell kein oder nur sehr eingeschränktes automatisches Übertragen von Kompetenz und Wissen in einem Aufgabenbereich zu einem anderen gibt. Algorithmen haben kein abstrahierendes, übergeordnetes Verstehen. 

Nichtsdestotrotz gibt es 

--

* Wahrnehmen
* Kommunizieren
* Planen
* Handeln
* Schlussfolgern
* Lernen


???
.task[COMMENT:]  


ein breites Spektrum an - typisch menschlichen - Kernfähigkeiten für schwache KI, wie situatives Wahrnehmen, Kommunizieren, Planen, Handeln, Schlussfolgern oder aber auch lernen.

---
.header[Künstliche Intelligenz]

## Schwache KI

Bestimmte Aufgaben werden genauso gut oder besser als von Menschen erledigt.

* Wahrnehmen
* Kommunizieren
* Planen
* Handeln
* Schlussfolgern
* **Lernen**


???
.task[COMMENT:]  

Dabei sind aktuell vor allem durch Daten selbstlernende Systeme im Fokus.

Lernen kann man als...  

--

> Lernen ist ein Prozess, durch den ein System die eigene Leistung auf Grund von Erfahrungen verbessert. - Herbert Simon


???
.task[COMMENT:]  

...einen Prozess beschreiben, durch den ein System die eigene Leistung auf Grund von Erfahrungen bzw. Daten verbessert.

Als Veranschaulichung was das für einen Algorithmus bzw. ein System bedeutet, hier ein kurzes Beispiel...


*Optinal*
* Herbert Alexander Simon (June 15, 1916 – February 9, 2001) was an American economist, political scientist and cognitive psychologist, whose primary research interest was decision-making within organizations and is best known for the theories of "bounded rationality" and "satisficing".[5] He received the Nobel Prize in Economics in 1978 and the Turing Award in 1975.
* Intelligence: reason, learn, plan, solve problems

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen


???
.task[COMMENT:]  

dass einen klassischen Anweisunggesteuerten Algorithmus mit einem lernenden vergleicht.

--

.center[<img src="img/programming_ml_01.png" alt="programming_ml_01" style="width:100%;">]


???
.task[COMMENT:]  

Als Beispiel haben wir folgendes Szenario: eine Fläche mit einer Breite von links nach rechts, mit links beginnend bei null bis zur rechten Seite mit dem Wert 100. Die Fläche soll nun in rechts und links unterteilt werden und ein Algorithmus soll für einen gegebenen Wert,

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_02a.png" alt="ml_02a" style="width:100%;">]


???
.task[COMMENT:]  

wie hier zum Beispiel den Wert 80, entscheiden, ob dieser Wert auf der linken Seite oder rechten Seite liegt.

In einer echten Vorlesung würde ich Sie nun fragen, ob sie Ideen für mögliche Anweisungen für haben, aber auf Grund der kürze der Zeit für die Probevorlesung bleibe ich beim frontalen Stil und hoffe, dass sie sich trotzdem mit einbezogen fühlen.

Also, klassische Anweisungen könnten wie folgt aussehen

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_02b.png" alt="ml_02b" style="width:100%;">]


???
.task[COMMENT:]  

Falls der Wert für den wir entscheiden wollen auf welcher Seite er liegt, größer als 50 ist, dann liegt er auf der rechten seite. Bei allen anderen Werten, also allen kleiner gleich 50, liegt der Wert auf der linken Seite.

Und hiermit habe sie auch gleich ein bisschen Programmieren gelernt.

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_02.png" alt="ml_02" style="width:100%;">]


???
.task[COMMENT:]  

Setzen wir nun den Wert 80 ein, sehen wir, dass 80 größer als 50 ist, wir somit in den Teil springen der besagt dass wir auf den Wert als auf der rechten Seite liegend bestimmen können.

Nun stellen wir uns die gleich Aufgabe vor, aber mit folgendem Szenario,

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_05.png" alt="ml_05" style="width:100%;">]


???
.task[COMMENT:]  

wir wissen eigentlich nichts über den Raum, also hier Wertebereiche, haben eine Reihe an Beispielen, 

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_07.png" alt="ml_07" style="width:100%;">]


???
.task[COMMENT:]  

von denen wir wissen, ob sie links oder rechts liegen und

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_08.png" alt="ml_08" style="width:100%;">]


???
.task[COMMENT:]  

bekommen wir nun einen neuen Wert rein entscheiden wir für diesen anhand der vorhandenen Daten, in diesem Fall zu Beispiel anhand der geringsten Differenz zu anderen Werten, ob wir ihn als links oder rechts einstufen. 

Und genau das ist Maschinelles Lernen

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_09.png" alt="ml_09" style="width:100%;">]


???
.task[COMMENT:]  

In der klassischen Programmierung geben wir Anweisungen und Daten im Vorfeld vor und berechnen dann anhand dieser Anweisungen das Ergebnis.

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_10.png" alt="ml_10" style="width:100%;">]

???
.task[COMMENT:]  

Beim maschinellen Lernen starten wir mit einer Reihe an möglichen Ergebnissen und versuchen anhand dieser Daten ein Programm zu erzeugen, dass uns für neue Daten die gleichen Ergebnisse liefert.

Oder noch mal anders formuliert, anstatt von Hand Software-Routinen mit einem bestimmten Satz von Anweisungen zu programmieren, um eine bestimmte Aufgabe zu erfüllen, wird die Maschine anhand großer Datenmengen und Algorithmen *trainiert*, damit sie lernt, wie sie die Aufgabe ausführen kann.

Einer der berühmtesten und auch mächtigsten Machine Learning Verfahren beruht auf

---
.header[Künstliche Intelligenz | Schwache KI | Machine Learning]

## Neuronale Netze


???
.task[COMMENT:]  

sogenannten Neuronalen Netzen. Erste künstlichen neuronale Netze wurden schon in den sechziger Jahren entwickelt

--

.center[<img src="img/nn_01.png" alt="nn_01" style="width:45%;"> <img src="img/nn_02.png" alt="nn_02" style="width:50%;">]
.footnote[[[Bild: entwickler.de](https://entwickler.de/online/neuronale-netze-teil-3-159773.html), [wiki](https://www.wikiwand.com/de/K%C3%BCnstliches_neuronales_Netz)]]


???
.task[COMMENT:]  

inspiriert von unserem Verständnis der Biologie des Gehirns und den Verbindungen zwischen den Neuronen. 


---
.header[Künstliche Intelligenz | Schwache KI | Machine Learning]

## Neuronale Netze

.center[<img src="img/nn_04.png" alt="nn_04" style="width:100%;">]  
.footnote[[[Bild: Sigs-Datacom]](https://www.sigs-datacom.de/trendletter/2019-11/2-ki-und-testen.html)]


???
.task[COMMENT:]  

Neuronale Netze können ganz grob so funktionieren, dass zum Beispiel für das Klassifizieren von Hundebildern in Hunderassen sich der Algorithmus zu nächste eine großen Menge an Bildern ansieht, denen je eine Hunderasse zugeordnet sind. Der Algorithmus merkt sich nun, welche Bildeigenschaften zu welcher Hunderasse gehören. Das ist die Trainingsphase, die man einmalig berechnen muss.

Dabei werden Bildeigenschaften auf verschiedenen Skalen betrachtet, wie hier zu sehen z.B. ganzeinfachen Kanten, nicht mehr als kleine Striche bis hin zu größeren Eigenschaften wie z.B. was wir als Körperteil beschreiben würden. 

---
.header[Künstliche Intelligenz | Schwache KI | Machine Learning]

## Neuronale Netze

.center[<img src="img/nn_04.png" alt="nn_04" style="width:100%;">]  
.footnote[[[Bild: Sigs-Datacom]](https://www.sigs-datacom.de/trendletter/2019-11/2-ki-und-testen.html)]

???
.task[COMMENT:]  

Wenn dann ein neues unbekanntes Bild klassifiziert werden soll, werden die Eigenschaften auf den verschiedenen Skalen mit den schon gelernten Mustern verglichen und das Label dem am ähnlichsten schon bekannten Muster ausgegeben.

Wichtig ist es hier zu verstehen, dass es um Ähnlichkeiten und Wahrscheinlichkeiten geht. Ergebnisse sind mit bestimmten Wahrscheinlichkeiten richtig, je nachdem wie ähnlich sie zu den gelernten Mustern sind. 

Wenn wir uns hier noch mal unser Beispiel ansehen

---
.header[Künstliche Intelligenz | Schwache KI]

## Anweisungen vs. Lernen

.center[<img src="img/ml_11.png" alt="ml_11" style="width:100%;">]


???
.task[COMMENT:]  

und als Wert die 49 bestimmen würden, würden wir auf basis der aktuellen Trainigsdaten, 49 der rechten Seite zu ordnen, da der Wert der 55 ähnlicher ist das der 40. Uns fehlen zwischen 40 und 50 Daten.

--

Wir brauchen sehr viele Daten!


???
.task[COMMENT:]  

Sprich für hochwertige ML Algroithmen brauchen wir sehr viele.

Und genau deswegen, sind diese Algorithmen erst relativ kürzliche so mächtig geworden. Nämlich seitdem immer mehr Daten und Rechenleistung zur für das Trainieren zur Verfügung stehen.

Und das bringt uns zu dem Begriff des 

---
.header[Künstliche Intelligenz | Schwache KI]

## Deep Learning


???
.task[COMMENT:]  

...Deep Learnings. 

---
.header[Künstliche Intelligenz | Schwache KI]

## Deep Learning

.center[<img src="img/dl_cat.png" alt="dl_cat" style="width:80%;">]
.footnote[[[Bild: Nvidia]](https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/)]


???
.task[COMMENT:]  

Fun fact, wie viele gute Momente des lebens beruht das Aufkommen von Deep Learning auf Katzenvideos.

Andrew Ng griff 2012 bei Google die alt bekannte Idee der künstlichen neuronalen Netzwerke auf und machte sie im wesentlichen einfach nur riesige, vergrößerte die Schichten und Neuronen um dann massive Datenmengen durch das System laufen zu lassen, um es zu trainieren. In Ngs Fall waren es Bilder aus 10 Millionen YouTube-Videos, auf die Google praktischerweise auch leicht zugriff hatte. Ng brachte das "deep" zum learning und setzte den Startpunkt des Einzugs von machinellen Lernalgorithmen in unser aller leben.

Machine Learning ist also eine ganz bestimmte Art von lernenden Algorithmen und damit eine Untermenge von KI Systemen im Allgemeinen und Deep Learning ist wiederum eine Untermenge von Machine Learning.

Und heute ist die Bilderkennung durch Maschinen, die mit Deep Learning trainiert wurden, in vielen Szenarien besser als der Mensch, und das reicht von Katzen


---
.header[Künstliche Intelligenz | Schwache KI]

## Machine Learning

.center[<img src="img/classification_02.png" alt="classification_02" style="width:71%;">  <img src="img/classification_03.png" alt="classification_03" style="width:16%;"><img src="img/classification_04.png" alt="classification_04" style="width:70%;">]  .footnote[[[Bild: Nature]](https://www.nature.com/articles/s41598-017-17858-1)]

???
.task[COMMENT:]  

bis zur Erkennung von Indikatoren für Krebs im Blut und Tumoren in MRT-Scans. Hier sind z.B. Bilder einzelner Zellen zu sehen anhand in derer ein Algorithmus zwischen normalen und Krebszellen unterscheiden und auffällige Merkmale markieren kann.

Dabei ist es auch wichtig zu verstehen dass

---
.header[Künstliche Intelligenz | Schwache KI]

## Machine Learning

.center[<img src="img/ml_types.png" alt="ml_types" style="width:100%;">]
.footnote[[[Bild: Analytics Vidhya]](https://medium.com/analytics-vidhya/which-machine-learning-algorithm-should-you-use-by-problem-type-a53967326566)]


???
.task[COMMENT:]  

...Neuronale Netze basierend auf gelabelten Trainigsdaten nur eine Möglichkeit von einer Vielzahl an verschiedenen ML Algorithmen darstellt. Die verschiedenen Algorithmen kommen alle mit ihren ganz eigenen Stärken, Schwächen und Einsatzgebieten.

Eine der größten Probleme bei diesen Verfahren ist es, dass sie sogenannte Black Boxes sind. Was bedeutet das bzw. warum ist das so?

---
.header[Künstliche Intelligenz | Schwache KI]

## Deep Learning

.center[<img src="img/go_network.png" alt="go_network" style="width:100%;">]  
.footnote[[[Bild: Library of Congress]](https://blogs.loc.gov/maps/category/game-theory/)]


???
.task[COMMENT:]  

Wie schon gesagt, für gute funktionierende System braucht man riesige Netzwerke das z.B. bestimmte Eigenschaften klassifiziert. Diese Eigenschaften sind aber eigentlich nichts anderes als Gewichte der Nodes im Graph, also Zahlenwerte. Die Muster und Merkmale anhand denen Klassifiziert werden sehen also 

---
.header[Künstliche Intelligenz | Schwache KI]

## Deep Learning

.center[<img src="img/matrix_01.png" alt="matrix_01" style="width:48%;"><img src="img/matrix_01.png" alt="matrix_01" style="width:48%;"><img src="img/matrix_01.png" alt="matrix_01" style="width:48%;"><img src="img/matrix_01.png" alt="matrix_01" style="width:48%;">]  
.footnote[[[Bild: Stack Exchange]](https://tex.stackexchange.com/questions/263307/creating-a-big-matrix)]


???
.task[COMMENT:]  

eigentlich irgendwie so aus. Es sind riesig geschachtelte Matrizen. Und die können unsere auf diesem Bereich sehr eingeschränkten Gehirne nicht verarbeiten und verstehen und das macht die Verfahren zu sogenannten Blackbox Verfahren.

Und auch noch mal zu den Trainigsdaten selbst. Wie gesagt, Andrew Ng hat das seine ersten Deep Learning Versuche mit 10 Millionen YouTube-Videos trainiert. Die kann auch kein Mensch durchgehen und gucken, ob das auch sinnvolles Datenmaterial ist.

---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen]

## Daten

Systeme, die auf maschinellem Lernen basieren, werden als besonders objektiv wahrgenommen.


???
.task[COMMENT:]  

Merkwürdigerweise wurde Daten basierte Verfahren als besonders objektiv wahrgenommen, alla Daten lügen nicht, aber...

--

.center[<img src="img/mirror_02.png" alt="mirror_02" style="width:50%;">]  


???
.task[COMMENT:]  

Aber man muss sich bewusst machen, dass die Daten von uns kommen...


---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen]

## Daten

Systeme, die auf maschinellem Lernen basieren, werden als besonders objektiv wahrgenommen.

.center[<img src="img/mirror_01.png" alt="mirror_01" style="width:50%;">]  


???
.task[COMMENT:]  

...quasi die Daten sind ein Spiegel von uns, unserer Gesellschaft und in den Systemen manifestieren sich somit alle unsere Fehler, alle unsere Vorurteile.

Es gibt in der Informatik den schönen Spruch, 

--

> Garbage in, garbage out...


???
.task[COMMENT:]  

Garbage in, garbage out... also wenn man Müll reingibt, kommt auch Müll wieder raus. Und genauso ist diesen Algorithmen. Und da es so großen Datenmengen sind, können wir sie nicht so einfach auf ungewollte mögliche systematische Fehler prüfen. Und diese systematischen Fehler lauern wirklich überall. 

Ich habe z.B. kürzlich mit eine neuen Kamera, die OakD getestet. Die Kamera enthält spezielle Hardware für die Berechnung von Neuronalen Netzen. Ein Beispiel die in der Dokumentation der Kamera enthalten ist, bestimmt das Geschlecht und Alter automatisch.

---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen | Daten]

## Systematische Fehler

.center[<img src="img/oakd.gif" alt="oakd" style="width:60%;">]  


???
.task[COMMENT:]  

Finde den Fehler. 

Während beim Alter noch eine gewisse Unsicherheit besteht, zweifelt das Programm nicht ein einziges mal daran dass ich männlich bin Und den Herstellen scheint das auch nicht aufgefallen zu sein. Naja.

Ein weiteres Problem sind die 

---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen | Daten]

## Energiekosten für das Trainieren  


???
.task[COMMENT:]  

Energiekosten für das Trainieren solcher Systeme.

--
*Eine durchschnittliche Person verbraucht ca. 5t CO2 pro Jahr.*

???
.task[COMMENT:]  

Als Anhaltspunkt: eine durchschnittliche Person verbraucht ca. 5t CO2 pro Jahr.

--
* 16 GB Datensatzes (BERT) = inneramerikanischer Flug / ca. 0.6t CO2

.footnote[.caps[Roy Schwartz, Jesse Dodge, Noah A. Smith, and Oren Etzioni]. 2020. Green AI. Commun. ACM 63, 12 (December 2020), 54–63. &  J. Hartmann, Academic Readings Presentation, SS21  ]

???
.task[COMMENT:]  

Das Trainieren mit einem grundlegenden, kleinem Datensatze für Spracherkennung liegt bei ca. 0.6t CO2, was in etwa einem inneramerikanischer Flug entspricht.

--
* Bilddatensatz (BigGAN) = transatlantischer Flug / ca. 1 to 2t CO2

???
.task[COMMENT:]  

Das Trainig mit einem modernen Bilddatensatz liegt schon bei 1-2 Tonnen, was einem transatlatischen Flug entspricht 

---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen | Daten]

## Energiekosten für das Trainieren  

*Eine durchschnittliche Person verbraucht ca. 5t CO2 pro Jahr.*

* 16 GB Datensatzes (BERT) = inneramerikanischer Flug / ca. 0.6t CO2

* Bilddatensatz (BigGAN) = transatlantischer Flug / ca. 1 to 2t CO2

* Experimente mit Transformer (z.B. GPT-3) = 50 Jahre einer durchschnittliche Person / ca. 250 t CO2  


.footnote[.caps[Roy Schwartz, Jesse Dodge, Noah A. Smith, and Oren Etzioni]. 2020. Green AI. Commun. ACM 63, 12 (December 2020), 54–63. &  J. Hartmann, Academic Readings Presentation, SS21  ]


???
.task[COMMENT:]  

und die Arbeit mit dem neusten Sprachmodellen liegt bei 250 Tonnen, was 50 Jahre einer durchschnittliche Person entspricht.

Wie gesagt, das Trainieren muss für ein System nur einmal durchgeführt werden. Aber in der Entwicklungsphase und in Forschungsgruppen oder allein für die Lehre passiert das durchaus regelmäßig. Und ich sage auch gar nicht, dass man die Herangehensweise deswegen verwerfen sollen, genauso wie ich nicht sage würde, dass man nie wieder fliegen darf. Aber man muss sich halt dessen bewusst sein, was man tut.



---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen | Daten]

## Energiekosten für das Trainieren   

.center[<img src="img/greenai_01.png" alt="greenai_01" style="width:70%;">]  

.footnote[.caps[Roy Schwartz, Jesse Dodge, Noah A. Smith, and Oren Etzioni]. 2020. Green AI. Commun. ACM 63, 12 (December 2020), 54–63. &  J. Hartmann, Academic Readings Presentation, SS21  ]

???
.task[COMMENT:]  

Auch ist es so dass die Forschung aktuell deutlich auf die Accuracy von Algorithmen fokussiert, also darauf die Ergebnisqualität z.B. von Klassifizierungen zu verbessern.

Die roten Balken repräsentieren wissenschaftlich Veröffentlichungen zu Accuracy in den Jahren 2018 und 19 wohingegen die grünen Balken die Paper repräsentieren die sich mit der Effizienz von Systemen beschäftigen.

Ok, soviel zu meiner kleinen Einführung in die KI. Zusammenfassend kann man sagen, dass


---
.header[Künstliche Intelligenz | Schwache KI | Maschinelles Lernen]

## Zusammenfassung

* Starke KI ⇨ Science Fiction


???
.task[COMMENT:]  

sogenannte Starke KI mit übergreifenden Fähigkeiten nachwievor Science Fiction ist.

--
* Schwache KI ⇨ Extrem mächtig
    * Machine Learning
    * Deep Learning

???
.task[COMMENT:]  

Schwach KI allerdings ist für bestimmte, klar definiert und abgesteckte Aufgaben extrem mächtig ist, vorallem durch Algorithmen, die auf maschinellem Lernen basieren. Für ein solches maschinelles Lernen braucht man

--
* Daten
    * Riesige Mengen
    * Systematische Fehler
    * Unflexibel


???
.task[COMMENT:]  

riesiege Datenmengen, die aktuell schwer zu kontrollieren sind und systematische Fehler enthalten können sind, die auch aktuell nur sehr schwer zu beheben sind.

Als nächste Schritte in der Forschung und Entwicklung sollten also ganzheitliche Ansätze verfolgt werden, die die Systeme aus verschiedenen Perspektiven betrachten und evaluieren und damit muss es ggf. auch eine 
re-priorisierung der Forschungsthemen geben.




--

### *Ende*

---
template: inverse

---
template:inverse

### Machine Learning

# Beispiel Sprachmodelle

---
.header[Machine Learning]

## Beispiel Sprachmodelle

.center[<img src="img/sprachmodelle_01.png" alt="sprachmodelle_01" style="width:100%;">]  


???
.task[COMMENT:]  

* Viel, vergleiseweise gut zu verarbeitende Daten vorhanden.
* Positive Anwendungsszenarien, wie z.B. Übersetzungssysteme, Sprachsteuerung, Verbesserungen von sprachlichen Fehlern
* https://www.lux-review.com/the-5-best-language-translation-apps/

---
.header[Machine Learning | Beispiel Sprachmodelle]

## State of the art: Transformer Text Generierung

.center[<img src="img/transformer_03.gif" alt="transformer_03" style="width:100%;">]


???
.task[COMMENT:]  

* https://transformer.huggingface.co/

---
.header[Machine Learning | Beispiel Sprachmodelle]

## Intelligent?

### Chinesisches Zimmer

.center[<img src="img/chinese-room-test.png" alt="chinese-room-test" style="width:70%;">]  

--

.center[<img src="img/chinese_rule.jpg" alt="chinese_rule" style="width:60%;">]

.footnote[[Bild: Startup Glide](https://startupglide.com/postulates-to-artificial-intelligence/)]


???
.task[COMMENT:]  

Das Chinesische Zimmer ist der Name für ein Gedankenexperiment des Philosophen John Searle. Mit seiner Hilfe versucht Searle die Meinung zu widerlegen, dass digitale Computer allein dadurch Bewusstsein erlangen könnten, dass sie ein passendes Programm ausführen.

Bei dem Gedankenexperiment stellt man sich einen geschlossenen Raum vor, in dem ein Mensch, der keinerlei Chinesisch versteht, in chinesischer Schrift gestellte Fragen – anhand einer in seiner Muttersprache verfassten Anleitung – in chinesischer Schrift sinnvoll beantwortet. Personen außerhalb des Raums folgern aus den Ergebnissen, dass der Mensch in dem Raum Chinesisch beherrscht, obwohl das nicht der Fall ist.

Das Experiment sollte zeigen, dass ein Computer ein Programm ausführen und regelbasiert Zeichenreihen verändern kann, ohne die Bedeutung der Zeichen zu verstehen. Die Fähigkeit, Syntax zu befolgen, soll nach Searle also nicht zu Semantik befähigen. Nach Searle müsste ein Computer dafür Intentionalität aufweisen.

Mit Hilfe seines Gedankenexperimentes wollte Searle nachweisen, dass es nicht ausreicht, dass eine programmierte Rechenmaschine den Turing-Test besteht, um als intelligent zu gelten. Erfolg im Turing-Test stelle also kein ausreichendes Kriterium für sogenannte starke künstliche Intelligenz dar. Darüber hinaus stellt es die komputationalen Theorien des Geistes in Frage.

Das Gedankenexperiment wird von Searle 1980 in seinem Aufsatz Minds, Brains, and Programs eingeführt

* https://www.wikiwand.com/de/Chinesisches_Zimmer
* https://towardsdatascience.com/the-history-of-artificial-intelligence-the-turing-test-c1d6777d2970
* https://startupglide.com/postulates-to-artificial-intelligence/
* https://www.wikiwand.com/en/Chinese_room



---
.header[Machine Learning | Beispiel Sprachmodelle]

## Systematische Fehler

--

.center[<img src="img/transformer_03.png" alt="transformer_03" style="width:100%;">]  

.footnote[Bild: J. Hartmann, Academic Readings Presentation, SS21]

---
.header[Machine Learning | Beispiel Sprachmodelle]

## Systematische Fehler

.center[<img src="img/transformer_04.png" alt="transformer_04" style="width:100%;">]  .footnote[Bild: J. Hartmann, Academic Readings Presentation, SS21]

---
.header[Machine Learning | Beispiel Sprachmodelle]

## Riesige Datenmengen

.center[<img src="img/language_models_01.png" alt="language_models_01" style="width:100%;">]  
.footnote[Bild: J. Hartmann, Academic Readings Presentation, SS21]



???
.task[COMMENT:]  

* 16 GB Datensatzes (BERT) = inneramerikanischer Flug / ca. 0.6t CO2
* Experimente mit Transformer (z.B. GPT-3) = 50 Jahre einer durchschnittliche Person / ca. 250 t CO2


---
.header[Machine Learning | Beispiel Sprachmodelle]

## Riesige Datenmengen

* Unflexibel
* Soziale Veränderungen, z.B. gendergerechte Sprache, lassen sich schwer einpflegen



---
.header[Machine Learning]

## Beispiel Sprachmodelle

.caps[Emily M. Bender, Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell]. 2021. **On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜** In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency, 610–623.



> ACKNOWLEDGMENTS  
> This paper represents the work of seven authors, but some were required by their employer to remove their names. The remaining listed authors are extremely grateful to our colleagues for the effort and wisdom they contributed to this paper.

.footnote[Bild: J. Hartmann, Academic Readings Presentation, SS21]

???
.task[COMMENT:]  

* https://www.wired.com/story/google-timnit-gebru-ai-what-really-happened/


---
template: inverse

### Künstliche Intelligenz
# *Und nun?*

---
.header[Künstliche Intelliganz]

# Die Nächsten Schritte

* Transparente Dokumentation und Kommunikation
* Ganzheitlichen Ansatz verfolgen
* Re-priorisierung der Forschung





