# **GameEngine.js**: A 2D game engine made for using HTML Canvas!

## **Still Under Development!**


**[npm package website](https://www.npmjs.com/package/@nikee_dev/gameengine_js)**

![npm](https://img.shields.io/npm/v/@nikee_dev/gameengine_js?color=Green&label=Current%20package%20version&style=flat-square)


### Examples:
**All examples to current features are available on examples folder (GitHub), or on** https://nikeedev.github.io/GameEngine_js

### Features:

**A game engine making website games that implements Canvas API, and has many useful functions and classes. Will be added more functions and features further!**

**List:**
 - ```ts 
    var name = new Rect(position: Vector2, size: Size, screenSize: Size);
   ```
   - Rect class draws you a rectangle into the canvas, you can change its position, size, and current screen size( for it to work )

<br>

- ```ts 
   var name = new Text(text: string, position: Vector2, screenSize: Size);
  ```
  - Text class draws you a text block into the canvas, you can change its text, position and current screen size( for it to work )

<br>

- ```ts
   var name = new Vector2(x: number, y: number);
  ```
  - Vector2 class for position for other classes. Can be used without the drawing classes.
  
<br>

- ```ts
   var name = new Size(width: number, height: number);
  ```
  - Size class for sizing numbers for other classes. Can be used without the drawing classes.
  
<br> 

- ```ts
   var name = new Sprite(imageSrc: string, position: Vector2, ScreenSize: Size);
  ```
  - Sprite class draws a sprite/image into canvas, you can change its source location of image, position and current screen size( for it to work ). You must first initialize sprite, before you can draw it.
  
<br>

- ```ts
   var name = new Screen(CanvasSize: Size);
  ```
  - Screen class makes it easy to start coding with GameEngine.js, it create you manually a \<canvas\> element, and also gathers from it 2D context, to make the GameEngine.js draw. After calling the class with `var name = new Screen(new Size(200, 200));`. You will need to initialize the screen, so it will use your custom size to create the canvas element with the context.

<br>

### License:

**This project is licensed with the MIT LICENSE. Please follow additional info about it, at LICENSE file.**

