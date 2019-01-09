# Dating Mechanism: Eine Linked Data Strategie zur interoperablen und nachvollziehbaren Modellierung relativer Chronologien am Beispiel südgallischer Terra Sigillata in Limes-Abschnitten

## Graphentechnologien 2019

**Florian Thiery<sup>1,3</sup> & Dr. Allard Mees<sup>2,3</sup>**

<sup>1</sup> Florian Thiery M.Sc. `thiery@rgzm.de` <a href="https://orcid.org/0000-0002-3246-3531" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">orcid.org/0000-0002-3246-3531</a>

<sup>2</sup> Dr. Allard Mees FSA `mees@rgzm.de` <a href="https://orcid.org/0000-0002-7634-5342" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">orcid.org/0000-0002-7634-5342</a>

<sup>3</sup> Römisch-Germanisches Zentralmuseum Mainz, Leibniz-Forschungsinstitut für Archäologie [`rgzm.de`](http://rgzm.de/), Kompetenzbereich Wissenschaftliche IT

**keywords**: `Linked Open Data`, `Chronologie` `Südgallische Terra Sigillata` `Allen's interval algebra` `Allen Kalkül`

Seit Mitte der 1990er Jahre stellt das RGZM (Römisch-Germanisches Zentralmuseum in Mainz) webbasierte Datenbanken mit hunderttausenden von Datensätzen aus verschiedenen archäologischen Disziplinen der Scientific Community zur Verfügung. Diese historisch gewachsenen, zumeist relationalen Datenbanken wurden in interdisziplinären, transnationalen Projekten erstellt und beinhalten oft „hidden assumptions” hinsichtlich Datierungen. Das Ziel des  Projekts „Dating Mechanism“ ist es, diese impliziten Informationen mittels semantischer Datenmodelle in Graphen sichtbar und verfügbar zu machen und sie als Linked Open Data (LOD) zu teilen. Diese interoperablen Daten sollen im Sinne der „reproducible research“ als Grundlage für Open Science der Forschungscommunity zur Verfügung stehen.

Insbesondere die Samian Research Datenbank[1] des RGZM beinhaltet fast 250'000 identifizierte Töpferstempel, die in der Archäologie auf traditioneller Art datiert werden. Dies wird gewöhnlich dadurch realisiert, dass "absolute Daten" in "from-to tables " erstellt werden, wobei die Realität viel komplexer ist. In der Tat basieren Datierungen von Terra Sigillata oft auf so genannten "dated sites" oder gar ganzen Limes-Abschnitten, die selbst von Terra Sigillata datiert werden. Man trifft also regelmäßig auf Kreisargumentationen. Dazu werden als erster Schritt Zeitintervalle mit offenen Anfangs- oder fehlenden End-Datierungen in eine relative Chronologie transformiert. Darüber hinaus können Zusatzinformationen, wie der Anteil an Töpfern, welche die Limes-Abschnitte gemeinsam haben, als Informationen für den Grad einer Verbindung (hier =Vagheit) zwischen zwei Limes-Abschnitten genutzt werden. In einem Reasoning-Prozess werden diese vagen Informationen ebenfalls mit ausgewertet um neue interferierte Information zu erzeugen, die bei der Beantwortung von Forschungsfragen behilflich sein können.

Zur Modellierung dieser Problematik, wird ein auf RDF (Resource Description Framework) basierendes semantisches Modell entwickelt, das zum Ziel hat, den Terra Sigillata -Datierprozess verifizierbar und transparent zu machen, um so neue Strategien für den maschinenlesbaren Zugriff – hier als LOD - auf archäologische Daten und Informationen in Form von Graphen zu ermöglichen.

Dieser Vortrag zeigt die Modellierung von Datierungsargumenten in einer relativen Chronologie, basierend auf Allens Intervall Algebra [2], in Kombination mit absoluten Datierungen. Dazu werden zwei prototypische Tools benutzt. Zum einen, das vom RGZM erstellte Tool „Alligator“ [3] zur Transformation einer Korrespondenzanalyse in RDF-modellierte Allen -Intervalle und zum anderen das von mainzed in Kooperation mit dem RGZM und dem i3mainz entwickelte „Academic Meta Tool“ (AMT) [4]. AMT ermöglicht die Modellierung von Vagheit in RDF-Graphen und ein „temporal reasoning“  nach Allen, sowie eine Visualisierung des Graphen und Download der Daten zur Verwendung in anderen Tools wie Neo4J.

Die Nutzung von Graphstrukturen ermöglicht es somit, Information und Interpretationen der hochgranulierten Daten zu modellieren, um so „hidden assumptions“ sichtbar zu machen und transparent bereitzustellen. Darüber hinaus können durch die Anwendung der Tools „Alligator“ und „AMT“ heterogene Daten und komplexe digitale Forschungsfragen im Umgang mit relativen Chronologien in den Datenrepositorien des RGZM standardisiert und interoperabel zur Verfügung gestellt werden. Somit können wir zeigen, dass Flexibilität im Datierungsprozess und Interoperabilität bei der Nachhaltigkeit und Wiederverwendung zwei Seiten eines Terra Sigillata–Datensatzes sind.

* [1] http://rgzm.de/samian
* [2] https://doi.org/10.1145/182.358434
* [3] https://rgzm.github.io/alligator/
* [4] http://academic-meta-tool.xyz

## Presentation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.abc.svg)](https://doi.org/10.5281/zenodo.abc)

## Live Demo

[![Demo](https://img.shields.io/badge/demo-dm--gt2019-brightgreen.svg?style=flat)](http://academic-meta-tool.xyz/gt2019/)

## Links

[![info](https://img.shields.io/badge/dm--gt2019-git repo-orange.svg?style=flat)](https://github.com/RGZM/dm-gt2019)

[![info](https://img.shields.io/badge/Academic Meta Tool-website-yellowgreen.svg?style=flat)](http://www.academic-meta-tool.xyz)
[![info](https://img.shields.io/badge/Academic Meta Tool-git repo-yellowgreen.svg?style=flat)](https://github.com/AcademicMetaTool/amt)

[![info](https://img.shields.io/badge/Samian Research-database-yellow.svg?style=flat)](http://rgzm.de/samian)

{% include footer.htm %}
