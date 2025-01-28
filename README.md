# Swarms
## Project Conclusions

-    Point and vector arithmetic are extremely useful for these algorithms. (It’s also useful for others such as drawing two- and three-dimensional graphics, other simulations such as in a spaceship game, orbital mechanics modeling, and so forth.)

-    The Boids algorithm simulates a flock or swarm by using the simple rules (1) move toward the flock’s center, (2) stay away from nearby Boids, and (3) match the velocities of nearby Boids. The milestones in this project added (4) move toward a target and (5) move away from obstacles.

-    The gravity Boids program uses slightly simpler forces that point (1) toward other Boids, (2) away from other Boids, (3) toward the target, and (4) away from obstacles. The force toward the target is divided by the distance, so it applies over large distances. The force toward other Boids is divided by the distance squared, so it applies at medium distances. The forces away from other Boids and obstacles are divided by the distance cubed, so they only apply at small scales.

-   Particle swarm optimization searches for optimal solutions. It is not guaranteed to find the best possible solution, but it often finds a good result. It does not require you to evaluate the objective function’s derivatives.

