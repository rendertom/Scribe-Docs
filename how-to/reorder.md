# Change the animation order

This section describes how to change the order of character animations.

> Follow the [Write](how-to/write) and [Animate](how-to/animate) steps to create a "itty-bitty" text using the Vibur font.

Once written and animated, the result should look similar to this:

![itty-bitty-1](../assets/animations/itty-bitty-1.gif)

Let's change the order of animation so the dots on the _i_ and the horizontal bars on the _t_ characters are animated at the end of the animation.

1. Select the shape layer and twirl down the Contents group to reveal the groups of each character.
2. Click on the **Add: >** button next to the **Contents** property to create a new empty group.
3. Rename this group to "accents" and make sure it is placed right after the last _y_ character.
4. Find all the _i_ and _t_ characters under the Contents group and reveal their contents.
5. Select all the property groups with names `Path i - 2` and `Path t - 2` and drag-and-drop them into the **accents** group that we created in step 2.

Once finished, the animation should look like this:

![itty-bitty-2](../assets/animations/itty-bitty-2.gif)
