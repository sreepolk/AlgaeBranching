# Algae Branching Mechanisms

Model 1:
This study begins with the recreation of a basic Turing reaction-diffusion model to generate stripe patterns. This initial model focused on simulating the interaction between two substances—an activator and an inhibitor—where the activator promotes its own growth while the inhibitor suppresses it. The system was governed by reaction and diffusion processes that drive pattern formation.

Model 2:
Next, I introduced apical cell behavior into the model. This was done by simulating an initial “bump” in the concentration of the activator, mimicking how an apical cell functions as a growth center. This adjustment allowed the system to form localized growth regions separated by areas of inhibition, resulting in structured periodic waves. However, at this stage, symmetrical growth patterns were observed, with both sides of the system growing at the same rate.

Model 3:
The third modification included the introduction of asymmetrical cell division. To achieve this, I implemented differential inhibition, where one side of the system grows faster than the other. This was achieved by applying less inhibition to the left side, allowing it to grow faster, while the right side was suppressed, activating only after a delay. This spatial variation in inhibition led to the formation of an asymmetrical growth pattern, mimicking the branching dynamics observed in biological systems.

Model 4:
Finally, I incorporated dynamic expansion into the model, where the width of the simulation would increase when the activator reached the edges of the system. This dynamic expansion mimicked continuous growth, similar to the behavior observed in biological systems like algae. The system maintained asymmetric growth through differential inhibition, where the left side continued to grow faster than the right, but with the added feature of expanding the simulation space to simulate growth over time.

Models 5 and 6:
These last two models are incomplete and reflect interpeak growth and the creation of 2D Turing patterns, respectively.
