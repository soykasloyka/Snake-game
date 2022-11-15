Rules of the game:

1. The player controls the movement of the snake, which crawls around the square field: up, down, right and left.
2. The snake cannot be stopped.
3. The goal of the game is to eat as many apples as possible, which appear in turn, in a random place on the playing field, as soon as the snake "swallows" the previous one.
4. With each new apple, the snake grows by one segment (occupies one cell more). In our game, at the start, the snake occupies three cells (it has three segments) and can grow up to 28.
5. As the snake grows, the speed of the game increases.
6. The snake cannot pass "through itself" or go out of the playing field.
7. The game ends in victory if the length of the snake has increased to 28 segments.
8. The game ends in a loss if it touches itself or the edge of the field.

The "game engine" logic and classes are in the com.javarush.engine.cell package, and in order to use them, the SnakeGame class must contain the following import:
import com.javarush.engine.cell.*;