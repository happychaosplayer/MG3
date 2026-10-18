# MG3
## Devlog
1. After making them member variables, the default values for floats are 0f, ints are 0, bools return false, and strings return null.
2. The Update() method is called every single frame because of the base class MonoBehaviour.
3. When declaring a variable in the TimerText class you can access variables and methods in the Timer class as long as they are public. We do this specifically in the TimerText class by creating an instance with the class Timer. Thus, you can display the remaining time by accessing the Timer class through the TimerText class every FRAME because of the Update() method.

.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)