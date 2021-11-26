# affichled

## Etape 1

Prendre le bloc lorsque secouer.


```blocks
input.onGesture(Gesture.Shake, function () {
	
})
```
## Etape 2

Prendre le bloc montrer l'icône et choisir la croix
et le glisser dans le bloc précédent

```blocks
input.onGesture(Gesture.Shake, function () {
    basic.showIcon(IconNames.Heart)
})
```
## Etape 3

Rajouter un bloc pause (ms) et mettre l'équivalent de 5s.

```blocks
input.onGesture(Gesture.Shake, function () {
    basic.showIcon(IconNames.Heart)
    basic.pause(5000)
})
```
### Etape 4

Enfin pour terminer, rajouter à la suite le bloc
effacer l'écran.
```blocks
input.onGesture(Gesture.Shake, function () {
    basic.showIcon(IconNames.Heart)
    basic.pause(5000)
    basic.clearScreen()
})
```
})

	
})