###################################
Konfigurationsmanagement Exercise 3
###################################

32. Richten Sie sich ein Repository auf GitHub ein – achten Sie darauf, 
dass es nicht leer ist. (z.B. README erzeugen lassen). (https://www.github.com)

33. Einerseits clonen Sie das Repository von GitHub um eine lokale Kopie davon zu
bekommen.

Welche Befehle benutzen Sie dafür?
**********************************

.. code:: bash
  git clone https://github.com/if17b041/ue3KFGM.git
  git lol
  > feef760 (HEAD -> master, origin/master, origin/HEAD) Initial commit
	
Was fällt Ihnen hinsichtlich der Historie auf?
**********************************************

.. code:: bash
	
  $ git lol
  * feef760 (HEAD -> master, origin/master, origin/HEAD) Initial commit

Recherchieren Sie die Details und beschreiben Sie hier Ihre Erkenntnisse!
*************************************************************************
	
.. code:: text

  git clone klont das remote repository und spiegelt es 1:1 lokal wieder

34. Andererseits richten Sie lokal in einem anderen Verzeichnis ein neues Repository ein und
verbinden Sie es mit dem Remote Repository auf GitHub und synchronisieren Sie!
Beschreiben Sie die Befehle dafür!

.. code:: bash

	git init .
	git remote add origin https://git.truh.in/truh/KFMG_Exercise03.git
	git pull origin master
	
35. Jetzt erstellen Sie in beiden Repositories neue Dateien mit unterschiedlichen Namen,
committen Sie und synchronisieren Sie jeweils mit dem Remote Repository 

was fällt Ihnen auf?
********************

.. code:: bash

Welche Befehle benutzen Sie? Beschreiben Sie Ihre Befehle.
**********************************************************

.. code:: bash


36. Bearbeiten Sie nun in beiden Repositories dieselbe Datei in derselben Zeile und erzeugen
Sie so einen Konflikt. Synchronisieren Sie abermals und beschreiben Sie Ihre neuen
Befehle und Erkenntnisse!

.. code: text


37. In einem Repository haben Sie nun eine neue Version fertig gestellt. Erstellen Sie einen
Tag mit der Version 1.0.0 und synchronisieren Sie mit dem Remote Repository! 

Welche Befehle nutzen Sie und welche Optionen bieten diese? 
***********************************************************

Synchronisieren Sie auch das zweite Repository sodass Sie auch den Tag bekommen.
********************************************************************************

38. Erstellen Sie nun in jedem Repository unterschiedliche Feature Branches und simulieren
die Entwicklung zweier Features unterschiedlicher Entwickler. Achten Sie darauf, dass erst
die neue Version mit integrierten Features auf dem Remote Repository landet! 

Welche Befehle benutzen Sie?
****************************

.. code:: bash


39. Erstellen Sie einen eigenen Deployment Branch und erstellen Sie in diesem Branch die
neuen Versionen inklusive Tags. Simulieren Sie abermals die Entwicklung neuer Features
für neue Minor Versionen (mind. 2). Der Deployment Branch soll die neuen Version
enhalten – der master Branch bleibt künftig für Major Versionen reserviert. Erstellen zuletzt
auch eine neue Major Version und synchronisieren Sie am Ende beide Remote
Repositories.

.. header::

    +-------------+--------------------+------------+
    | ###Title### | Jakob Klepp,       | 2017-10-03 |
    |             | Michael Steiner    |            |
    +-------------+--------------------+------------+

.. footer::

    ###Page### / ###Total###
