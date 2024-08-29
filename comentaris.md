# Comentaris

De vegades cal explicar per a què serveixen parts concretes del codi. Afortunadament, Python us permet satisfer les vostres necessitats. Podeu deixar notes especials anomenades comentaris. Són especialment útils per a principiants. Al llarg d'aquest curs, sovint farem servir comentaris per explicar els nostres exemples.

## Què és un comentari?
Els comentaris de Python comencen amb un hash, #. Tot el que hi ha després del hash fins al final de la línia es considera un comentari i s'ignorarà en executar el codi.

```python
print("Això s'executarà.")  # Això no s'executarà
```

A l'exemple anterior, podeu veure el que PEP 8 anomena un comentari <strong> <a rel="noopener noreferrer nofollow" target="_blank" title="A Python, una línia es refereix a un comentari escrit a la mateixa línia que el codi. Proporciona context o explicació addicional per al codi. Els comentaris en línia han de tenir un espai després de la marca hash (#) i dos espais entre el final del codi i la marca hash. Segons PEP 8, la longitud dels comentaris hauria de limitar-se a 72 caràcters i es pot dividir en diverses línies per formar un bloc. És una bona pràctica fer sagnar el comentari al mateix nivell que l'enunciat que explica.">en línia</a></strong>. És un comentari  escrit a la mateixa línia que el codi.

Un comentari també pot fer referència al <a rel="noopener noreferrer nofollow" target="_blank" title="A Python, un bloc de codi es refereix a un grup de línies consecutives de codi que s'executen com a unitat única. | Normalment es defineix per una línia de capçalera, també coneguda com a línia que comença amb una paraula clau com ara 'si', 'per', 'mentre' o 'def'. La línia de capçalera va seguida d'una o més línies de codi sagnades que formen el bloc. Aquestes línies sagnades només s'executen si la condició especificada a la línia de capçalera és certa. El sagnat adequat és crucial perquè el bloc de codi funcioni correctament. Els blocs de codi es poden imbricar, és a dir, un bloc de codi pot contenir un altre bloc de codi.">bloc de codi</a> que el segueix:

```python
# Imprimeix tres números
print("1")
print("2")
print("3")
```

Tenim la intenció d'utilitzar els comentaris principalment amb finalitats d'aprenentatge. Ara és el moment d'esbrinar com comentar el codi correctament.

## Format dels comentaris

Encara que és fàcil escriure un comentari, anem a discutir com fer-ho segons les millors pràctiques.

Per començar, hi hauria d'haver un espai després d'una marca hash. Per als comentaris en línia, hi hauria d'haver dos espais entre el final del codi i el signe hash. Posar més de dos espais entre el final del codi i la marca hash és acceptable, però el més habitual és que hi hagi exactament dos espais.

```python
print("Aprendre Python és divertit!") # Aquest és un format de comentari correcte
print("PEP-8 és important!")#Aquest és un exemple molt dolent
```
Sagna el teu comentari al mateix nivell que l'afirmació que explica. Per exemple, l'exemple següent és incorrecte:

```python
    # aquest comentari està al lloc equivocat
print("Aquesta és una declaració per imprimir.")
```

Un comentari no és una ordre de Python: no hauria de ser massa llarg. Després de PEP-8, la longitud dels comentaris s'hauria de limitar a 72 caràcters. És millor dividir un comentari llarg en diverses línies. Podeu fer-ho afegint una marca hash al començament de cada línia nova:

```python
# Imagineu que aquest és un exemple d'un comentari molt llarg que
# hem de repartir-nos en tres línies, així que continuem
# escriu-ho fins i tot aquí.
print("El comentari llarg anterior explica aquesta línia de codi.")
```

Els comentaris que abasten diverses línies s'anomenen comentaris de diverses línies o blocs. A Python, no hi ha cap manera especial d'indicar-los.

Podeu trobar comentaris de diverses línies entre <a rel="noopener noreferrer nofollow" target="_blank" title="A Python, una cometa triple és un conjunt de tres cometes (simples o dobles) que s'utilitzen per denotar una cadena de diverses línies. A diferència de les cometes simples o dobles, que s'utilitzen per a cadenes d'una sola línia, les cometes triples permeten la creació de cadenes que abasten diverses línies. Sovint s'utilitzen per a cadenes de documentació (docstrings) a Python, que proporcionen una breu descripció d'un mòdul, funció o classe. Les cometes triples es poden col·locar en línies separades, i la descripció detallada comença a la mateixa posició que la primera cita de la primera línia de documentació.">**cometes triples**</a>: <kbd>"""..."""</kbd>. No obstant això, us recomanem que utilitzeu diverses línies que comencen amb marques **`hash`** per a aquest propòsit. Aleshores, el vostre codi complirà la guia d'estil oficial. Les cometes triples es reserven per a les cadenes de documentació, les cadenes de documents <a rel="noopener noreferrer nofollow" target="_blank" title="A Python, una docstring és una cadena literal que proporciona documentació per a una classe, mòdul o funció. S'escriu com la primera declaració en la definició d'un mòdul, classe, mètode o funció, i descriu breument el seu comportament i com utilitzar-lo, incloent quins paràmetres cal passar a la funció. Les cadenes de documents es poden escriure entre cometes simples o dobles, però sovint s'utilitzen cometes triples per a cadenes de documents de diverses línies. Hi ha diverses propostes de millora de Python (PEP) dedicades a les cadenes de documents, com ara PEP 257 i PEP 287, que descriuen les convencions per escriure cadenes de documents.">**`docstrings`**</a> per abreujar-les. També són informatius, però el seu ús es limita a funcions, mètodes i molts altres casos.

## Resum

En aquest tema, hem après què són els comentaris i per a què serveixen. Els punts principals són:

* Els comentaris s'utilitzen per explicar per a què serveixen parts concretes del vostre codi.
* Els comentaris comencen amb un hash, #.
* Els comentaris s'ignoren durant l'execució del codi.
* Els comentaris poden estar a sobre d'un fragment de codi, en línia o formar un bloc.

Hi ha regles específiques de format de comentaris que hauríeu de seguir segons PEP 8:

* Hi hauria d'haver un espai després d'una marca hash.
* Per als comentaris en línia, hi hauria d'haver dos espais entre el final del codi i la marca hash.
* La longitud del comentari ha de limitar-se a 72 caràcters. Podeu dividir un comentari llarg en diverses línies formant un bloc.
* Sagna el teu comentari al mateix nivell que l'afirmació que explica.
