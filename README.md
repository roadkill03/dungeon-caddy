dungeon-caddy
=============
- Drag n drop
- Sprite animations
- Text renderer
- Touch ready
- Sounds

Frameworks
----------

pixijs
Sound framework??

Pattern
-------

Entity component system

Components
----------

- Position(x, y)
- Sprite(images, animations)
- Health(value)
- Damage(value)
- Range(value)
- Magic(value, alignment)
- Craft(combine, target)

Entities
--------

- Item(Position, Sprite)
- ManaPotion(Position, Sprite, Magic)
- HealthPotion(Position, Health, Sprite)
- Axe(Position, Sprite, Damage)
- Bow(Position, Sprite, Damage, Range)
- Sword(Position, Sprite, Damage)
- Hammer(Position, Sprite, Damage)
- Wand(Position, Sprite, Damage, Magic, Range)