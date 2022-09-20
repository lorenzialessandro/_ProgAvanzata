# Diagramma delle classi UML
[[1 introduzione diagramma delle classi UML.pdf]]

---
`13/09`

## Diagrammi UML
- strutturali
	- diagramma delle classi e degli oggetti
- comportamentali
	- casi d'uso
	- stati e transizioni
- architetturali
	- componenti
	- sviluppo

## Oggetti in UML
un oggetto modello un elemento che ha vita propria, ha un identificatore ed è un istanza di una classe

## Classi in UML
una classe modello insieme omogenei di oggetti con proprietà statiche o dinamiche associate, è descritta da
- nome
- insieme di proprietà
- insieme di operazioni

## Classi e Istanza
- tra oggetto di una classe C e classe C : arco : Instance-of
	- oggetto : estensionale
	- classi : intensionale

## Attributi 
- proprietà locale della classe con nome e tipo di valori associati
- ogni attributo valido per tutte le istanze

## Associazioni
- associazione tra classe C1 e classe C2 : relazione matematica tra insieme di istanze di C1 e quelle di C2
- modellano proprietà che coinvolgono più classi
- *ex: Classe Libro con associazione "autore" a Classe Persona *
- <u>link</u>: istanze di associazioni 
- <u>ruolo</u>: informazioni che specificano ruolo della classe
	- nome vicino a linea dell'associazione vicino a classe
	- slide 15 - 16
- <u>associazioni possono avere attributi</u>


## Generalizzazione
- coinvolge una superclasse e una o più sottoclassi : classi derivate
- is-a
- <u>ereditarietà</u>: ogni proprietà della superclasse è anche una proprietà della sottoclasse, e non si riporta esplicitamente nel diagramma
- posso avere diverse generalizzazioni della stessa classe 
	- si mette nome del criterio su freccia
	- slide 24
- tipi
	- <u>disgiunta o non disgiunta</u>
		- sottoclassi disgiunte a coppie
	- <u>completa o non completa</u>
		- unione delle istanze delle sottoclassi è uguale all'insieme delle istanze della superclasse

