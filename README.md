AllowMe
=========
>Visual aid for your users in giving you browser's permission such as cam or mic

![Animated GIF](http://s30.postimg.org/a1pe6r78f/allow_Me.gif)

___

Getting Started
=========


**Step 1: Installation through bower **

    bower install allow-me

**Step 2: Add both allowMe.js and allowMe.css into your index.html**

**Step 3: Running allowMe**
```javascript
    var permission = new allowMe();
    permission.show('container', {
    
        headerText: "Click allow to turn on your web cam ",
        headerFontSize: "40px",
        headerFont: "PT Sans, serif",
    
        captionText: "Clicking allow means you'll provide camera and microphone access allowing the other parties will hear and see you.",
        captionFontSize: "20px",
        captionFont: "PT Sans, serif",
    
        backdropColor: '#000',
        backdropOpacity: 0.7,
    
        arrowColor: "#FFFFFF",
        arrowSize: 1.5
    });
```

That's it!
___

Options
=========

- **headerText:** your header text
- **headerFontSize:** (optional) font-size for your header text 
- **headerFont** (optional) font for your header text
* **captionText:** (optional) your header text
* **captionFontSize:** (optional) font-size for your caption text
* **captionFont:** (optional) font for your caption text

- **backdropColor:** (optional), color of your backdrop in HEX, default #000 (black)
- **backdropOpacity:** (optional) opacity of your backdrop, default 0.5 
    
* **arrowColor:** (optional) color of your arrow in hex, default "#FFFFFF" (white) 
* **arrowSize:** (optional) size of your arrow, default 1 