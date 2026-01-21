---
layout: default
title: Your First Game
nav_order: 2
---

# Your First Game: Dodge!

In this tutorial, you'll create a simple dodge game where a player avoids falling objects.

## Prerequisites

- A web browser
- Access to [MakeCode Arcade](https://arcade.makecode.com/)

## Step 1: Create a New Project

1. Go to [arcade.makecode.com](https://arcade.makecode.com/)
2. Click **New Project**
3. Name your project "Dodge Game"

## Step 2: Create Your Player

First, we'll create a sprite for the player to control.

```blocks
let mySprite = sprites.create(img`
    . . . . . . . . . . . . . . . .
    . . . . . 5 5 5 5 5 5 . . . . .
    . . . . 5 5 5 5 5 5 5 5 . . . .
    . . . 5 5 5 5 5 5 5 5 5 5 . . .
    . . 5 5 5 5 5 5 5 5 5 5 5 5 . .
    . . 5 5 5 5 5 5 5 5 5 5 5 5 . .
    . . . . . . . . . . . . . . . .
`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)
```

## Step 3: Add Falling Objects

Now let's create objects that fall from the top of the screen.

## Step 4: Add Collision Detection

When the player touches a falling object, the game ends!

## Step 5: Add Scoring

Keep track of how long the player survives.

---

## Challenge

Can you modify the game to:
- Make objects fall faster over time?
- Add different types of objects worth different points?
- Add power-ups?

---

[Back to Home](/)
