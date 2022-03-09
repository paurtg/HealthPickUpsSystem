# PickUps System
Add this single component to a 3D object that is being used as a main player in your game. This component will record your player's health and will affect it when in contact with  other chosen objects. This will be done by changing a simple UI system attached to the player controller. 

## Contents

This component is made from the following behaviours:
- `Health system`
- `Interactible pick-ups`

And the following state:
- `PickUps`


### PickUps

When added to a 3D object, in this case a main character controller, this component manages the health of your player. Two objects are added as examples of this package. One object will be used as a damaging object - when in contact with this one, the health bar of your player will decrease and will instantiate a particle system. The second one will be used as a healing object and when in contact with it, it will increase or restore a part of your player's health and will also instantiate another particle system. This will be represented by lowering the slider created as a UI health system. In order for this to work, a canvas needs to be added to the project, followed by an child empty object with two child objects, one as a border (not necessary) and one as a bar, which will be representing the player's health. A slider will need to be added into the empty object, followed by `Transition` and `Navigation` being changed to `None`. Lastly, adjusting the slider's `Max Value` and `Value` itself. 
After being added, the image representing the health bar will need to be dragged into the inspector, as well as the particles for each type of items/pick-ups and the health bar slider. 




