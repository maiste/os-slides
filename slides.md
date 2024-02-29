---
theme: the-unnamed
class: text-center
highlighter: shikiji
lineNumbers: true
drawings:
  persist: false
mdc: true
themeConfig:
  color: '#F3EFF5'
  background: '#161C2C'
  code-background: '#0F131E'
  code-border: '#242d34'
  accents-teal: '#88C0D0'
  accents-yellow: '#B48ead'
  accents-red: '#BF616A'
  accents-lightblue: '#8FBCBB'
  accents-blue: '#81A1C1'
  accents-vulcan: '#0E131F'
  header-shadow: rgba(0, 0, 0, 0.15) 1.95px 1.95px 2.6px;
  default-headingBg: var(--slidev-theme-accents-yellow)
  default-headingColor: var(--slidev-theme-accents-vulcan)
  default-background: var(--slidev-theme-background)
  center-headingBg: var(--slidev-theme-accents-blue)
  center-headingColor: var(--slidev-theme-accents-vulcan)
  center-background: var(--slidev-theme-background)
  cover-headingBg: var(--slidev-theme-accents-teal)
  cover-headingColor: var(--slidev-theme-accents-vulcan)
  cover-background: var(--slidev-theme-background)
  section-headingBg: var(--slidev-theme-accents-lightblue)
  section-headingColor: var(--slidev-theme-accents-vulcan)
  section-background: var(--slidev-theme-background)
  aboutme-background: var(--slidev-theme-color)
  aboutme-color: var(--slidev-theme-background)
  aboutme-helloBg: var(--slidev-theme-accents-yellow)
  aboutme-helloColor: var(--slidev-theme-background)
  aboutme-nameColor: var(--slidev-theme-accents-red)
title: Open Source 101
layout: cover
background: rgb(22, 28, 44)
---

# Open Source 101

<!--
- Remercier les gens d'être venu :)<br />
- Micro sondage sur l'Open source<br />
- Est ce qu'on peut contribuer en live à Réact ?<br />
-->

---

# Introduction

"Je vais contribuer à React !"

<div class="image-center">

![React Front page](/assets/introduction_react_main.png)

</div>

<!--
- Introduire le collègue expérimenté sur l'Open Source <br />
-->

---

# Introduction

"OK ! Je vais corriger un bug. Est ce que c'est bien comme premier ticket à régler ?"


<div class="image-center">

![React bug page](/assets/introduction_react_find_issue.png)

</div>

<!--
- Comment choisir une bonne issue pour commencer ?
-->

---

# Introduction

"On m'a parlé de **fork** mais je ne comprends pas trop ce que c'est..."

<div class="image-center">

![React fork page](/assets/introduction_react_fork.png)

</div>

<!--
- Le retour du collègue expérimenté
- Qu'est que c'est un fork ?
-->

---
layout: center
---

# Ce sont des phrases familières ?

<!--
- Phrase entendu en discutant avec des gens et lors de la soirée Open Source<br />
- Les gens perdus<br />
-->

---

# Qui suis-je ?

<style>
img {
    border-radius: 50%;
    width: 250px;
    margin-right: 100px;
}

.whoami {
    margin-top: 50px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

</style>

<div class="whoami">
    <img src="/assets/profile.jpg" />
    <ul>
        <li>Maiste</li>
        <li>Tombé dans l'Open Source il y a 7 ans</li>
        <li>email : dev@maiste.fr</li>
        <li>github : @maiste</li>
    </ul>
</div>

<!--
- En 2017 -> 7 ans<br />
- Jobs sur des projets Open Source 2 ans<br />
- Ici pour parler d'OS, ce que veut dire, comment rentrer monde pas forcément accessible<br />
-->




---
layout: section
---

<!--
###########################
# Histoire et définitions #
###########################
-->

# Il était une fois...

<!--
Pour comprendre, histoire et d'où vient.
-->

---
transition: slide-up
---

# Historique

<ul>
    <li v-click><strong>Début du logiciel</strong> : académiciens et chercheurs</li>
</ul>

<!-- Financer par l'armée, des universitaires donc papiers accessibles à tout le monde -->

---
transition: slide-down
---

# Historique - Début

Les universités et l'armée


<div class="image-center">

![Grace Hopper](/assets/grace_hopper.jpg)

</div>

<!--
- Grace Hopper
- 1er compilateur COBOL en 1959<br />
- Travail sur FORTRAN (toujours très utilisé dans le calcul intensif)
-->

---
transition: slide-up
---

# Historique

<ul>
    <li><strong>Début du logiciel</strong> : Académiciens et chercheurs</li>
    <li v-click>
        <div class="oneline">
            <p>
                <strong>Années 70</strong> : Séparation du logiciel et de l'hardware car anti-compétitif
            </p>
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                <path fill="currentColor" d="M16 11H8a1 1 0 0 1-1-1V7a5 5 0 0 1 10 0v3a1 1 0 0 1-1 1M9 9h6V7a3 3 0 0 0-6 0Z" opacity=".5"></path>
                <rect width="16" height="13" x="4" y="9" fill="currentColor" rx="3"></rect>
            </svg>
        </div>
    </li>
</ul>

<!-- Les choses se gattent dans les 70s -->

---
transition: slide-down
---

# Historique - Années 70

<style>

img {
    margin-top: 50px;
    max-height: 400px;
}

p {
    margin-left: 20px;
    margin-right: 20px;
}

</style>

<div class="image-center">

![IBM_logo](/assets/ibm_logo.svg)

<p> VS </p>

![USA Flag](/assets/USA_flag.png)

</div>

<!--
- Materiel + logiciels -> ensemble<br />
- Gouv USA vs IBM antitrust : 17 Janvier 1969 -> Logicies préinstallés sont anti-compétitifs<br />
- Logiciel = entité à part entière<br />
- Copyright Act - 1976 : logiciel appartient à son auteur<br />
-->

---
transition: slide-up
---

# Historique

<ul>
    <li><strong>Début du logiciel</strong> : Académiciens et chercheurs</li>
    <li>
        <div class="oneline">
            <p>
                <strong>Années 70</strong> : Séparation du logiciel et de l'hardware car anti-compétitif
            </p>
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                <path fill="currentColor" d="M16 11H8a1 1 0 0 1-1-1V7a5 5 0 0 1 10 0v3a1 1 0 0 1-1 1M9 9h6V7a3 3 0 0 0-6 0Z" opacity=".5"></path>
                <rect width="16" height="13" x="4" y="9" fill="currentColor" rx="3"></rect>
            </svg>
        </div>
    </li>
    <li v-click><strong>Septembre 1983</strong> : Création du GNU Manifesto par Richard Stallman</li>
</ul>

<!-- Création OS ouvert + logiciels accessible -->

---
transition: slide-down
---

# Historique - GNU Manifesto

La suite de programmes GNU

<div class="image-center">

![GNU Logo](/assets/GNU_Logo.png)

</div>

<!-- Première mention de code redistribué -> emacs -->

---
transition: slide-up
---

# Historique

<ul>
    <li><strong>Début du logiciel</strong> : Académiciens et chercheurs</li>
    <li>
        <div class="oneline">
            <p>
                <strong>Années 70</strong> : Séparation du logiciel et de l'hardware car anti-compétitif
            </p>
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                <path fill="currentColor" d="M16 11H8a1 1 0 0 1-1-1V7a5 5 0 0 1 10 0v3a1 1 0 0 1-1 1M9 9h6V7a3 3 0 0 0-6 0Z" opacity=".5"></path>
                <rect width="16" height="13" x="4" y="9" fill="currentColor" rx="3"></rect>
            </svg>
        </div>
    </li>
    <li><strong>Septembre 1983</strong> : Création du GNU Manifesto par Richard Stallman</li>
    <li v-click><strong>Octobre 1985</strong> : Création de la Free Software Foundation</li>
    <li v-click><strong>Février 1986</strong> : Publication de la Free Software Definition</li>
</ul>

<!-- Idées aboutissent création FSF \+ définition de Free Software -->

---
transition: slide-down
---

# Free Software Definition

Les quatre libertés :

<v-clicks>

1. La liberté <mark>d'exécuter</mark> le programme, pour tous les usages ;
2. La liberté <mark>d'étudier</mark> le fonctionnement du programme et de <mark>l'adapter</mark> à ses besoins ;
3. La liberté de <mark>redistribuer</mark> des copies du programme ;
4. La liberté d'améliorer le programme et de <mark>distribuer</mark> ces améliorations au public, pour en faire profiter toute la communauté.

</v-clicks>

<br />

<v-click>

> "You should think of free as in free speech, not as in free beer."
> -- _Richard Stallman_

</v-click>

<!--
1. N'importe qui peut utiliser mon code pour tous les usages<br />
2. N'importe qui peut regarder mon code<br />
3. Que ce soit donner ou en vendre des copies<br />
4. Travailler sur le code soucre et le repartager<br />

Attention Free != Gratuit
-->

---
transition: slide-up
---

# Historique

<ul>
    <li><strong>Début du logiciel</strong> : Académiciens et chercheurs</li>
    <li>
        <div class="oneline">
            <p>
                <strong>Années 70</strong> : Séparation du logiciel et de l'hardware car anti-compétitif
            </p>
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                <path fill="currentColor" d="M16 11H8a1 1 0 0 1-1-1V7a5 5 0 0 1 10 0v3a1 1 0 0 1-1 1M9 9h6V7a3 3 0 0 0-6 0Z" opacity=".5"></path>
                <rect width="16" height="13" x="4" y="9" fill="currentColor" rx="3"></rect>
            </svg>
        </div>
    </li>
    <li><strong>Septembre 1983</strong> : Création du GNU Manifesto par Richard Stallman</li>
    <li><strong>Octobre 1985</strong> : Création de la Free Software Foundation</li>
    <li><strong>Février 1986</strong> : Publication de la Free Software Definition</li>
    <li v-click><strong>Février 1998</strong> : Cission et création de l'Open Source Initiative</li>
</ul>

<!--
- FSF trop utopiste<br />
- Pas assez compatible buisiness<br />
- Cission avec FSF et communauté<br />
-->

---

# Open Source Definition

Les 10 pointes de l'OSI :

<v-clicks>

1. <mark>La redistribution libre</mark>
2. <mark>Le code source</mark>
3. <mark>Les œuvres dérivées</mark>
4. <mark>L'intégrité du code source de l'auteur</mark>
5. La non-discrimination contre des personnes ou groupes
6. La non-discrimination contre des champs d'application
7. La distribution de licence
8. La licence ne doit pas être spécifique à un produit
9. La licence ne doit pas restreindre d'autres logiciels
10. La licence doit être neutre sur le plan technologique

</v-clicks>

<!--
1. Pas interdir vendre ou donner logiciel comme composant + pas droit d'auteurs ni commission<br />
2. Avec l'executable ou accessible + pas obfusqué<br />
3. Modification et applications dérivés avec même condition de licence -> protège utilisateur<br />
4. Auteur peut forcer sous forme de patch = autorise modification mais avec intégrité du code de base -> protège l'auteur<br />
5. Respect la loi du pays (ex: sanction) mais par elle-même pas restrictive sur les personnes ou groupes<br />
6. Pour ne pas restreindre les utilisations commerciales = encourarger l'Open Source dans les affaires<br />
7. Droit du programme pour tous sans licence supplémentaire -> pas de fermeture par NDA<br />
8. Les droits pas dépendre  fait partie d'une distribution logicielle spécifique -> pas de fermeture par extraction -> toujours licence <br />
9. Si fait partie ensemble pas de contamination -> devs font leurs choix -> OK distribuer logiciel close source avec un open source<br />
10. Pour lutter contre les licences qui implique un acte explicite d'acceptation pour établir un contrat<br />

Ah ! Complexe mais 4 points à retenir
-->
---

# Et nous dans tout ça ?

<div class="image-center">

![GIF Afraid](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWE2OXFrZ3U0Mnh6bGdhdm5pM3g0bmtrdjR1aXU1a3V4ZWw4ZHh5NiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/RHOwWKH5OY7buuGHNi/giphy.gif)

</div>

<!-- Beaucoup de choses à se souvenir ? -->

---

# Et nous dans tout ça ?

<v-clicks>

- Le Libre (Free Software) est lié à <mark>l'utilisateur</mark>
- L'Open Source est lié au <mark>logiciel</mark>
- Le code ouvert
- La collaboration
- _(Plus une vision de l'OSI)_

</v-clicks>

<!-- 
- Pas notre problème ici<br />
- Libre = user<br />
- Open Source = logiciel<br />
- On ne garde que deux choses en tête pour ce talk<br />
-->

---
layout: center
---

# A priori sur l'Open Source en tant que développeuse et développeur ?

<!-- *Interroger le public* -->

---
transition: fade-out
---

# A priori ?

- C'est compliqué de contribuer
- Je ne sais pas par où commencer
- Je ne sais pas quoi faire
- Je n'ai pas le niveau (syndrôme de l'imposteur)
- Je ne code pas

<!-- Entendu ceux là -> Mais les deux derniers = pas argument -->

---
layout: center
---

![GIF Stop it](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOGtham85bWdmeXVzMWxhMXFtdm5lMDRjMDR1c3psZTg3NzQxZGR5cSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/zCpYQh5YVhdI1rVYpE/giphy.gif)

<!-- Pas entendre ça -->

---
layout: center
transition: fade
---

#  On remonte ses manches et on s'y met ?

<!-- Sujet : contribuer puis pourquoi ouvrir son code -->






---
layout: section
---

<!--
################################
# Contribution à l'Open Source #
################################
-->

# Contribuer à l'Open Source

---
transition: slide-up
---

# Pas que du code

<v-click>
<li>Corriger de la documentation</li>
</v-click>

<!-- Important mais sous côté -->

---

# Pas que du code - Documentation

Les typos

<div class="image-center">

![img](/assets/contribute_doc_typos.png)

</div>

<v-click>
<Arrow class="arrow" x1="800" y1="540" x2="600" y2="430" />
</v-click>

<!-- Docusaurus : une simple typo dans le code -->

---
clicks: 2
---

# Pas que du code - Documentation

Maintenir à jour le code et la documentation

<div class="image-center">

![img](/assets/contribute_docs_outdated.png)

</div>

<div v-click="[1,2]">
<Arrow class="arrow" x1="50" y1="360" x2="200" y2="270" />
</div>

<div v-click="[2,3]">
<Arrow class="arrow" x1="50" y1="450" x2="200" y2="350" />
</div>



<!--
    Option de docusaurus dans build -> compile
-->

---
transition: slide-down
---

# Pas que du code - Documentation

En ajoutant les information manquantes

<div class="image-center">

![img](/assets/contribute_doc.png)

</div>

<v-click>
<Arrow class="arrow" x1="80" y1="520" x2="220" y2="390" />
</v-click>

<!--
- Propre contribution:<br />
- Appli OTP manquante mais très utilisée dans le monde OS
-->

---
transition: slide-up
---

# Pas que du code

- Corriger de la documentation

<v-click>
<li>Participer sur les forums</li>
</v-click>

<!--
- Sous estimé<br />
- Important car soulage mainteneuses / mainteneur
-->

---
transition: fade
---

# Pas que du code - Forum

<mark>Discourse</mark>


<div class="image-center">

![img](/assets/contribute_forum.png)

</div>

<!--
- Instance de discource, un logiciel Open Source pour faire des forums<br />
- Logiciel Open Source Caddy<br />
- Répondre sur des forums aux questions -> forger des liens avec la communauté<br />
- OCaml, Rust, Golang, etc (slides suivante)<br />
-->

---
transition: fade
---

# Pas que du code - Forum

Golang


<div class="image-center">

![img](/assets/golang_discourse.png)

</div>

---
transition: fade
---

# Pas que du code - Forum

OCaml


<div class="image-center">

![img](/assets/ocaml_discourse.png)

</div>

---
transition: fade
---

# Pas que du code - Forum

Rust


<div class="image-center">

![img](/assets/rust_discourse.png)

</div>

---
transition: fade
---

# Pas que du code - Forum

Kotlin

<div class="image-center">

![img](/assets/kotlin_discourse.png)

</div>

---
transition: slide-down
---

# Pas que du code - Forum

Kubernetes

<div class="image-center">

![img](/assets/kube_discourse.png)

</div>

---
transition: slide-up
---

# Pas que du code

- Corriger de la documentation
- Participer sur les forums

<v-click>
<li>Financer les projets</li>
</v-click>

<!--
- Connu<br />
- Souvent bénévole<br />
- Hauteur des moyens<br />
-->

---

# Pas que du code - Financer

<style>
img {
    height: 400px;
}
</style>

Avec **GitHub Sponsors**

<div class="image-center">

![img](/assets/zod_sponsor.png)

</div>

<v-click>
<Arrow class="arrow" x1="900" y1="400" x2="700" y2="500" />
</v-click>

<!-- Exemple avec GitHub Sponsors -->

---

# Pas que du code - Financer

Avec l'**Open Collective**

<style>
img {
    height: 400px;
}
</style>

<div class="image-center">

![img](/assets/webpack_open_collective.png)

</div>

<!--
- Open Collective = plateforme pour transparence budget<br />
- Page webpack de l'Open Collective<br />
-->

---
transition: slide-down
---

# Pas que du code - Financer

Avec l'**Open Collective**

<div class="image-center">

![img](/assets/webpack_balance.png)

</div>

<!-- On peut voir aussi le budget des différents projets qu'on utilise -->

<v-click>
<Arrow class="arrow" x1="900" y1="200" x2="750" y2="300" />
</v-click>

---

# Et le code dans tout ça ?

<v-clicks>

- Corriger un bug
- Développer une feature
- Aider les mainteneurs

</v-clicks>

<v-click>

<div class="image-center margin-50">

## ... sur un projet <mark>que l'on utilise</mark>

</div>

</v-click>

<!--
- On connait le logiciel<br />
- On l'apprécie<br />
- On sait pourquoi il existe<br />
-->

---

# Contribuer - L'art de la fourchette

<div class="image-center">

![img](/assets/work_with_fork.png)

</div>

<!--
- fork = une copie du dépôt<br />
- Travailsur notre copie / fork<br />
- PR sur le fork <br />
- Pas 3000 branches sur le dépot original<br />
-->

---
transition: slide-up
---

# Contribuer - Le manuel

Commencer avec un peu de lecture

<div class="image-center">

![img](/assets/contribute_file_to_read.png)

</div>

<v-click>
<Arrow class="arrow" x1="10" y1="330" x2="120" y2="430" />
</v-click>

<!--
- Fichiers importants à lire sur un dépôt<br />

1. Le README -> Informations de base<nr />
-->

---
transition: slide-down
---

# Contribuer - Le manuel

Le README

<div class="image-center">

![readme](/assets/contribute_readme.png)

</div>

<!-- Spring Boot -> Installation & Getting Started -->

---
transition: slide-up
---

# Contribuer - Le manuel

Continuons la lecture

<div class="image-center">

![img](/assets/contribute_file_to_read.png)

</div>

<v-click>
<Arrow class="arrow" x1="10" y1="220" x2="110" y2="320" />
</v-click>

<!--
    2. Le CONTRIBUTING.md -> Comment faire / est ce que c'est le cas ?<br />
-->

---
transition: slide-down
---

# Contribuer - Le manuel

Le CONTRIBUTING

<style>
img {
    height: 400px;
}
</style>

<div class="image-center">

![contributing](/assets/contribute_contributing.png)

</div>

<!-- Spring Boot -> Les issues pour tracker les bugs -->

---
transition: slide-up
---

# Contribuer - Le manuel

Finissons notre lecture


<div class="image-center">

![img](/assets/contribute_file_to_read.png)

</div>

<v-click>
<Arrow class="arrow" x1="10" y1="180" x2="110" y2="280" />
</v-click>

<!--
3. CODE_OF_CONDUCT -> Les règles de communication au sein du projet<br />
- Peut révéler des sujets interdits = pas ban <br />
-->

---
transition: slide-down
---

# Contribuer - Le manuel - CODE_OF_CONDUCT

Le CODE OF CONDUCT

<style>
img {
    height: 400px;
}
</style>

<div class="image-center">

![readme](/assets/contribute_code_of_conduct.png)

</div>

<!-- Spring Boot -> Règles de bonnes ententes -->

---

# Contribuer - Le B.A-BA

<v-clicks>

1. Demander avant de se lancer
2. Commencer petit
3. Faire des choses reproductibles : bugs ou tests
4. Les mainteneurs sont des humains : <mark>ça ne sert à rien de s'énerver</mark>

</v-clicks>

<v-click>

<br />

<div class="image-center margin-50">

### ... la même <mark>rigueur</mark> que sur nos projets finalement ;)

</div>

</v-click>

<!--
- Pas travailler pour rien<br />
- Typos pour rentrer dans le projet et se faire connaître<br />
- Bug = gagner du temps<br />
- Test = regression sur gros projets = plus facile à suivre les changements<br />
- Bénévoles = pas toujours le temps<br />
- Même hygiène que sur projets pro<br />
-->

---

# Contribuer - En cas de refus

Mon changement n'est pas accepté :

<ol>
    <v-click>
        <li>Tant pis !</li>
    </v-click>
</ol>

<v-click>

<div class="image-center">

![GIF No](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGQ3Mm5zcWVpbnBpOWg3cjVyMmJxYzFyd2c1eHpibjQ0aDB3cWtncSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/66H4XkI1OWAOA/giphy.gif)

</div>

</v-click>

<!-- Leur projet pas le votre -> tant pis -->


---


# Contribuer - En cas de refus

Mon changement n'est pas accepté :

<ol>
    <li>Tant pis !</li>
    <v-click>
        <li>Maintenir un fork :</li>
    </v-click>
    <ul>
        <v-click>
            <li>Garder les changements du dépôt original</li>
        </v-click>
        <v-click>
            <li>Suivre les versions de release</li>
        </v-click>
    </ul>
</ol>

<!--
- J'utilise mon changement ou il est important pour un groupe de gens<br />
- Soft-fork<br />
-->

---

# Contribuer - En cas de refus

Mon changement n'est pas accepté :

<div class="image-col">

<ol>
    <li>Tant pis !</li>
        <li>Maintenir un fork :</li>
    <ul>
        <li>Garder les changements du dépôt original</li>
        <li>Suivre les versions de release</li>
    </ul>
</ol>



![GIF No God No](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExcmY0MDBpd3c5bmc4cGg4MGt0Y3F6dDBkY2wzeXNnZnI3b3F6Y282aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/hyyV7pnbE0FqLNBAzs/giphy.gif)

</div>

<!--
= beaucoup de travail
-->

---
transition: slide-up
---

# Contribuer - En cas de refus

Mon changement n'est pas accepté :

<ol>
    <li>Tant pis !</li>
    <li>Maintenir un fork :</li>
    <ul>
        <li>Garder les changements du dépôt original</li>
        <li>Suivre les versions de release</li>
    </ul>
    <v-click>
        <li>Hard Fork : un nouveau projet ?</li>
    </v-click>
</ol>

---

# Contribuer - Hard Fork

Example notable de Hard fork :

<div class="image-center">

![img](/assets/maintain_a_fork_opentofu.png)

</div>

<!--
    - On peut en citer plein d'autres :<br />
    - LibreOffice -> OpenOffice (licence)<br />
    - Ubuntu -> Debian (Choice)<br />
    - Blink (Chrome) -> WebKit (MacOs) -> Khtml (Linux) <br />
    - MariaDB -> MySQL (Acquis par Oracle)<br />
-->


---
layout: center
---

<!--

#################################
# Rendre son projet Open Source #
#################################
-->

# Un jour je serai le meilleur mainteneur

<!-- De l'autre côté du miroir -->

---

# Disclaimer

Ce n'est <mark>pas</mark> le monde des <mark>bisounours</mark>

<div class="image-center">

![GIF Aw, man](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzIxN3ZyZjYwOXB4emYwb3N3enZlaWh0MG9hc292Zm10c3c3NGJoOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lS1H8QDzB9BbQUhHL2/giphy.gif)

</div>

<!-- Tout n'est pas tout rose -->

---

# Disclaimer

Burnout

<div class="image-center">

![img](/assets/maintaineur_burnout_flappy_bird.png)

</div>

<!-- 
- Solus -> disparu trop travail<br />
- Courant avec charge de travail<br />
-->

---

# Disclaimer

Insultes et demande intempestives

<div class="image-center">

![img](/assets/maintaineur_warning.png)

</div>

<!--
- Log4j -> bénévoles -> grosses entreprises (Google, Amazon)<br />
- Vagues de haine car plusieurs failles (y compris grossess boîtes)<br />
- Bénévoles mais code accessible = gens avoir tous les droits != services<br />
-->

---

# Disclaimer

Vol de projet _(ouvert à débat)_

<div class="image-center">

![img](/assets/maintaineur_mongoDB_license.png)

</div>

<!--
- MongoDB et Elastic à cause d'Amazon qui expose les services sans retour<br />
- Débat ouvert par rapport à la licence<br />
-->

---

# Disclaimer

- Burnout / pressions
- Insultes
- Demande intempestives
- Vol de projets

<br />

<v-click>

<div class="image-center margin-50">

### ...comme dans la société mais <mark>protégez-vous !</mark>

</div>

</v-click>

<!--
- Connaître ses limites<br />
- Dire non<br />
- Respecter soi<br />
-->

---

# Pourquoi le faire

Ça vaut le coup ?

<div class="image-center">

![GIF DO it](https://media0.giphy.com/media/GcSqyYa2aF8dy/giphy.gif?cid=ecf05e471qfhkmbj7owmpa9x8hmh4rf1p1a4wqm6ae83ho64&ep=v1_gifs_related&rid=giphy.gif&ct=g)

</div>

<!-- Malgré les galères ? Oui -> sinon pas là pour en parler -->


---

# Pourquoi le faire

<v-clicks>

- Relecture par les pairs: qualité du code
- Améliorer la sécurité du code (relatif à l'utilisation du code)
- Rencontrer des gens du domaine
- Ne pas réinventer la roue
- S'intégrer à un écosystème déjà ouvert

</v-clicks>

<!--
- Qualité de code avec regards extèrieurs<br />
- Sécurité -> sur gros projet et à condition d'avoir un système pour remonter les failles<br />
-->

---
transition: slide-up
---

# Les choses importantes à savoir


<v-clicks>
<ul>
    <li>Ouvrir le code si on se sent prêt</li>
    <li>Choisir une licence</li>
</ul>
</v-clicks>

<!--
- README: comment compiler en local et lien vers comment contribuer<br />
- CONTRIBUTING: les informations sur PRs, issues, etc <br />
- licence = compliqué<br />
-->

---
transition: slide-down
---

# Les choses importantes à savoir

Choisir une licence

<div class="image-center">

![img](/assets/maintaineur_choose_license.png)

</div>

<!-- Important pour le mode de propagation : OPEN  = MIT vol de projet -->

---

# Les choses importantes à savoir

<ul>

<li>Ouvrir le code si on se sent prêt</li>
<li>Choisir une licence</li>

<v-clicks>
<li>Remplir le README</li>
<li>Remplir le CONTRIBUTING.md</li>
</v-clicks>

</ul>

<!--
- README: comment compiler en local et lien vers Contribution<br />
-->

---
transition: slide-up
---

# Les choses importantes à savoir

<ul>
    <li>Ouvrir le code si on se sent prêt</li>
    <li>Choisir une licence</li>
    <li>Remplir le README</li>
    <li>Remplir le CONTRIBUTING.md</li>
    <v-click>
    <li>Utiliser des templates d'issues</li>
    </v-click>
</ul>

<!-- CONTRIBUTING: les informations sur PRs, issues, etc -->

---

# Les choses importantes à savoir

Templates d'issues

<div class="image-center">

![img](/assets/contribute_issues.png)

</div>

<!--
- Fait gagner du temps et cadre les choses<br />
-->

---
layout: center
---

<!--
######################
# Soirée Open Source #
######################
-->

# La soirée Open Source

<!--
Idée vient des questions de la soirée Open Source
-->

---

# La soirée - Les retours


- Merci aux participantes, aux participants et à Takiveille

<div class="image-center">

![GIF Solid](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbDhlcnU3ZmQyOGNwa3U4dmx5aWllMGhtNzk4a2JodzhleTdzMXp3MSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/y2qhz4wPA2XlK/giphy.gif)

</div>

<!-- Merci pour tout -->

---

# La soirée - Les retours


- Merci aux participantes, aux participants et à Takiveille
- 25 personnes
- 3 PRs ouvertes sur des dépôts Open Source

<!-- Mais on s'y est mal pris -->

---

# La soirée - Les retours

<v-clicks>

- La soirée n'avait pas le <mark> bon état d'esprit</mark> : ne pas participer pour participer
- Sur un autre format, Hacking Night :
  - Projets personnels
  - Coding challenges
  - <mark>Coder ensemble sur des projets</mark>

</v-clicks>

<!--
- Pas la bonne approche !<br />
- Open Source parce que raison de contribuer pas parce qu'on veut dire qu'on a contribué<br />
--> 

---
layout: center
---

# Conclusion

---

# On récapitule ?

<v-clicks>

- Contribuer sur des projets que l'on <mark>utilise</mark> et que l'on <mark>apprécie</mark>
- À la hauteur de <mark>ses moyens</mark>
- Se mettre <mark>à la place de</mark> la mainteneuse ou du mainteneur
- Ouvrir son code pour des projets qui <mark>s'y prêtent</mark>
- Ouvrir son code si l'on pense que l'on <mark>est prêt</mark>

</v-clicks>

<!--
- Parler de beaucoup de choses donc on récapitule !
-->

---

# Ouverture

Open Data

<div class="image-center">

![img](/assets/opendata_parus.png)

</div>

<!-- 
- Une brique parmi tant d'autres<br />
- Données non critiques à disposition<br />
- Ville de Paris<br />
- Sncf<br />
-->

---

# Ouverture

Open Hardware

<div class="image-center">

![img](/assets/conclusion_open_hardware_arduino.png)

</div>

<!-- Arduino modifié les circuits = projet hackable -->

---

# Ouverture

Open Science


<div class="image-center">

![img](/assets/conclusion_open_sciences_arxiv.png)

</div>

<!--
- Reproductibilité des expériences et accessibilités<br />
- Faire avancer connaissances générales<br />
- Renforcer la confiance<br />
-->

---

# Ouverture

Open Knowledge

<div class="image-center">

![img](/assets/conclusion_open_knowledge.png)

</div>

<!--
- Les Wikis publiques, la connaissance ouverte pour agrandir plutôt que toujours réinventer<br />
- Contribuer au savoir collectif<br />
-->

---
layout: center
---

# Aucun de nous ne sait ce que nous savons tous, ensemble.

-- Euripide

---

# Merci pour votre attention !

<div class="image-center">

![GIF Love](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbHVoNHVtYW1tNnNya2Mxb3V0OGh0ODFuNnhzamI3eTByenNiN3psaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/R6gvnAxj2ISzJdbA63/giphy.gif)

</div>

<!--
- Merci écoute<br />
- Code sera Open Source sur GitHub<br />
-->

---
layout: center
---

# Vous avez des questions ?

---
layout: two-cols
---

# Sources

<style>
h1 {
    margin-bottom: 5px;
}
</style>

- Wikipédia :
  - [Open Source](https://en.wikipedia.org/wiki/Open_source)
- Opensource.com :
  - [What is Open Source](https://opensource.com/resources/what-open-source)
  - [What's the difference between open source software and free software](https://opensource.com/article/17/11/open-source-or-free-software)
- Opensource.org (OSI) :
  - [The Open Source Definition](https://opensource.org/osd/)
- Red Hat
  - [L'Open Source, qu'est que c'est ?](https://www.redhat.com/fr/topics/open-source/what-is-open-source)
- Digital Ocean :
  - [The Difference Between Free and Open Source Software](https://www.digitalocean.com/community/conceptual-articles/free-vs-open-source-software)

::right::

- Amazon :
  - [Open Source](https://aws.amazon.com/fr/what-is/open-source/)
- Youtube:
  - ["The Hard Parts of Open Source" by Evan Czaplicki](https://www.youtube.com/watch?v=o_4EX4dPppA)
  - ["A survival guide to open source" par Alexandre Fauquette.](https://www.youtube.com/watch?v=a30KjK59zgw)
  - ["The Economics of Programming Languages" by Evan Czaplicki (Strange Loop 2023)](https://www.youtube.com/watch?v=XZ3w_jec1v8)
- PimCore:
  - [Open Source your company](https://pimcore.com/en/why-open-source)
- Google :
  - [Why OpenSource](https://opensource.google/documentation/reference/why)
- Supabase :
  - [Why you should Open Source your company](https://supabase.com/blog/should-i-open-source-my-company)
