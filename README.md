
# Unity Simple Transformations

This repository contains a Unity scene with three spheres that demonstrate basic transformations: translation, rotation, and orbiting.

## Project Setup

1. **Download the repository:** Clone or download this repository.
2. **Open the scene:** Open the `Scene` folder and double-click the `.unity` file to open the scene in Unity.

## Scripts

### Translation

This script moves the sphere up and down in the Y-axis within a specific range (`[-1, 1]`).

### Rotation

This script rotates the sphere around its Y-axis clockwise or counter-clockwise.

### Orbit

This script orbits the sphere around a smaller sphere called `Sphere_center` on the Y-axis. The sphere can orbit clockwise or counter-clockwise. The sphere's rotation relative to its own Y-axis is not important. The `RotateAround()` method is used for this implementation.

### Orbit-Bonus 

This script achieves similar results to the `Orbit` script but without using the `RotateAround()` function. The sphere's position is manually updated to achieve the rotation effect. The sphere's rotation relative to its own Y-axis is not important.

## Usage

Run the scene in Unity and observe the sphere movements.

## Features

* Simple implementation of basic transformations.
* Clear and well-documented code.
* Easy to understand and modify.
