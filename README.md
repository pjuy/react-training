# react

## spécificités

- Virtual DOM : permet de tracker les modifications entre l'ancien et le nouveau DOM virtuel. Met à jour le vrai DOM avec uniquement ce qui est nécessaire.
- Server side rendering

## Avantages de react

- Small Components.
- Ecrire du JavaScript dans du HTML.
- States : On ne se préoccupe plus de listeners, tout est géré à travers les states. Quand un state se met à jour, l'appli se met à jour.
- Declarative :
  - - de méthodes disponibles donc - de code. On ne se focalise plus sur 'comment je fais ?' mais sur 'qu'est-ce que je veux faire ?'
  - moins de variables intermédiaires dont on modifie la valeur en itérant. On agit directement sur l'objet initial.
- Unidirectionnel : On ne gère que les states. L'UI se mettra à jour en fonction.

## Lexique de react

- Component : fonction qui retourne du code HTML + des valeurs dynamiques en JS.
- Router : permet de lier une page à un component.

## Astuces

- différence react/react-dom : react-dom permet de rendre le DOM sur le net. React permet de rendre sous un autre format (comme une console ?).

# npm

- npm init -y : -y permet de créer directement le fichier package.json avec les param par défaut
- npm scripts : permettent d'associer un mot clé à une commande complexe.

# Webpack

## Avantages

Récupérer plusieurs modules.
Appliquer des transformations dessus.
Rendre sous forme d'un seul gros fichier.

# babel

Permet de transformer/compiler le code.
EcmaScript en version ultérieur/antérieur.
Dans le cadre de react : .jsx en .js.

#Axios
AJAX requests.
