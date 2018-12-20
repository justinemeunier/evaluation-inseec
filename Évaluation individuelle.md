# Évaluation individuelle

## Programmation - Coaching

```
Nom : Meunier
Prénom : Justine
URL de votre compte Github : https://github.com/justinemeunier
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
C'est un mode de communication qui permet d'échanger entre différents programmes (client et serveur). Le client envoie des demandes et le serveur y répond.
```



 ### 2. HTML est un langage côté... 

```
balises
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
div {
    color: pink;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap une plateforme qui regroupe des bouts de codes afin de confectionner son site internet.

```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
        <link rel="stylesheet" href="styke.css">
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="row">
    <div class="col-sm-4">
        <p>Google</p>
    </div>
    
    <div class="col-sm-4">
        <p>Microsoft</p>
    </div>
 
    <div class="col-sm-4">
        <p>Apple</p>
    </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="row">
    <div class="col-sm-4">
        <img src="https://cdn.vox-cdn.com/thumbor/Pkmq1nm3skO0-j693JTMd7RL0Zk=/0x0:2012x1341/1200x800/filters:focal(0x0:2012x1341)/cdn.vox-cdn.com/uploads/chorus_image/image/47070706/google2.0.0.jpg" style="width: 2.5cm;height: 2cm; alt="..." class="rounded">
        </div>
     <div class="col-sm-4">
         <img src="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg" style="width: 3cm;height: 2cm; alt="..." class="rounded">
        </div>
        <div class="col-sm-4">
           <img src="https://image.freepik.com/free-icon/apple-logo_318-40184.jpg" style="width: 2cm;height: 2cm; alt="..." class="rounded">
        </div>
    </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="d-flex justify-content-around">
    div class="row">
        <div class="col-sm-4">
            <img src="https://cdn.vox-cdn.com/thumbor/Pkmq1nm3skO0-j693JTMd7RL0Zk=/0x0:2012x1341/1200x800/filters:focal(0x0:2012x1341)/cdn.vox-cdn.com/uploads/chorus_image/image/47070706/google2.0.0.jpg" alt="..." style="width: 3.5cm;height: 2cm;>
            </div>
        <div class="col-sm-4">
            <img src="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg" alt="..." class="rounded" href="#">
        </div>
        <div class="col-sm-4">
            <img src="https://image.freepik.com/free-icon/apple-logo_318-40184.jpg" alt="..." class="rounded" href="#">
        </div>
    </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
# Variables

```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
Prenom = "Justine"
Nom = "Meunier"
Github = "https://github.com/justinemeunier"

puts Prenom
puts Nom
puts Github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
A = "674"
B = "311"
C = "A%B"

puts C 

# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gem est une bibliothèque de codes réutilisables.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une API permet de profiter des services d'un site sans passer par l'interface du site.
On peut, par exemple, tweeter en utilisant les clés API de ces services.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
puts "quel est votre nom?"
nom = gets.chomp
puts "Bonjour " + nom

if hour = 15
    puts "Bonjour"

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour <= 12
    
# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

