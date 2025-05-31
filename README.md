# TFG-catalan-models
Aquest repositori pertany al codi del TFG [Títol], de Mireia Almena Rodríguez.

En aquest estudi s’han analitzat quatre models extensos de llenguatge (LLMs) amb l’objectiu d’avaluar-ne la qualitat lingüística en català i observar la possible interferència del castellà. S’ha comparat un model monolingüe en català (**Catalan BERTa-v2**) amb tres models multilingües (**X-MOD**, **TwHIN-BERT** i **XLM-V**). A través d’un programari dissenyat en Python, s’ha comprovat que el model monolingüe és el que mostra una major adequació a la normativa del català, tot i que també reflecteix usos no normatius freqüents entre els parlants, cosa que també indica un ús descriptiu de la llengua.

Paral·lelament, s’han utilitzat oracions procedents del projecte CONTACT, centrat en el català d’herència en contextos bilingües, per analitzar si els models són capaços de detectar patrons de contacte lingüístic. Els resultats mostren una certa capacitat per identificar estructures gramaticals en contextos anafòrics, però no s’han detectat patrons consistents en el marcat diferencial d’objecte ni en l’alternança entre els verbs ser i estar.

En resum, l’estudi evidencia que els LLMs generen tant estructures normatives com no normatives, fet que obre el debat sobre el seu paper en la preservació i normalització del català, així com sobre la necessitat de regular-ne el desenvolupament per garantir un ús lingüísticament adequat. 

Contingut del **repositori**:

- datasets/: Conjunts de dades utilitzats en l'estudi
- codi/: Fitxer d'execució principal (Jupyter Notebook)
- resultats/: Fitxers de resultats CSV
- README.md: Aquest fitxer
