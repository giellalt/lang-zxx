# Test document for Mermaid graphics

# Simple graph

```mermaid
graph TD;
	A-->B;
	A-->C;
	B-->D;
	C-->D;
```

# Another simple graph

```mermaid
graph LR;
	A-->B;
	A-->C;
	B-->D;
	C-->D;
	A-->D;
	D-->D;
```

# A pie chart

```mermaid
pie
  title Pets adopted by volunteers
  "Dogs" : 386
  "Cats" : 85
  "Rats" : 35
  "Hros" : 55
```

# A sequence diagram

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```

# A state diagram for some simple lexicon structure

Below this text there should be a state diagram:

```mermaid
stateDiagram-v2
direction LR
[*] --> Root
Root --> Prefixes
Root --> NounRoot
Root --> Verb
Root --> Adjective
Root --> Pronoun
Root --> Adverb
Root --> Subjunction
Root --> Conjunction
Root --> Particle
Root --> Adposition
Root --> Punctuation
Root --> Symbols
Root --> Interjection
Root --> Abbreviation
Root --> Acronym
Root --> ProperNoun
Root --> Numeral
```

Above here there should be a state diagram. It should look like the following (taken from [mermaid.live](https://mermaid.live)):

[![](https://mermaid.ink/img/pako:eNptUcFqhDAQ_RWZY1kvPXpYkLaHQpFlhV6aHqIZ24iZkTGRyrL_3rhswUgvYebx3ps83gVaNggFTF57fLb6S7TL50dFxgq23jJlb2dFHw-fWZ4fszOzV7S-t_Uk2NkfnDZQxYF2rHeUZrOWpl-dZ0yMmKIwYc2prA5NH-j2pQ36xPQPetLibTtg4jfyZPe8VRr0Dq0X1_CwDfVKHqXH_ZmyaQRnu9eXbUyzuDTeiFKlCavgUPSgCA4QJ6etiUVcFGWZAv-NDhUUcTTY6TB4BYqukRpGE6t6MdazQNHpYcID6OC5XqiFwkvAP9K9zzvr-gurIKp2)](https://mermaid.live/edit#pako:eNptUcFqhDAQ_RWZY1kvPXpYkLaHQpFlhV6aHqIZ24iZkTGRyrL_3rhswUgvYebx3ps83gVaNggFTF57fLb6S7TL50dFxgq23jJlb2dFHw-fWZ4fszOzV7S-t_Uk2NkfnDZQxYF2rHeUZrOWpl-dZ0yMmKIwYc2prA5NH-j2pQ36xPQPetLibTtg4jfyZPe8VRr0Dq0X1_CwDfVKHqXH_ZmyaQRnu9eXbUyzuDTeiFKlCavgUPSgCA4QJ6etiUVcFGWZAv-NDhUUcTTY6TB4BYqukRpGE6t6MdazQNHpYcID6OC5XqiFwkvAP9K9zzvr-gurIKp2)

# Final comment

There are no graphs after this point
