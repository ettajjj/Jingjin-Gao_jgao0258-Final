# Jingjin-Gao_jgao0258-Final



### Project Overview

This project uses the p5.js library, combined with course content and additional resources, to create animations of an apple tree growing and a rain effect. Users can control the animations with interactive buttons, and the responsive canvas feature ensures a flexible and immersive experience.

--- 

### Interaction Guide

- **Start Growth Animation**: Click the “Start Growth” button to start the tree growth animation, where the tree structure gradually enlarges.
- **Rain Animation**: Click the “Start Rain” button to start the rain effect, and click the “Pause Rain” button to pause the raindrops. Raindrops fall from the top and disappear at the bottom.
- **Resize**: Adjusting the browser window size will automatically scale the canvas and content to fit the screen dimensions.

---

### Animation Mechanics

In my design, I chose a Time-Based approach as the primary method for driving animations, using time to control both the tree growth and raindrop movement to achieve the final effect. The time-based factor enables the tree growth animation to have a smooth, gradual expansion, while the raindrops fall at a constant speed, creating a visual effect of continuous rainfall.

---

### Image Properties and Animation Details

- **Growth Animation**: Each time the `startGrowth` function is called, the `shrinkFactor` variable gradually increases, allowing the tree elements to grow from a smaller scale to their full size, simulating natural growth.
- **Raindrop Animation**: Raindrops are generated periodically and move downwards using the `move` function. Once they reach the bottom of the screen, they are removed from the array to keep the visuals clear.
- **Adjustable Scale Factor**: The `scaleFactor` dynamically adjusts based on the window size, ensuring the canvas and graphics display at an appropriate scale across various screen sizes.
- **Overall Scaling of the Apple Tree**: Using `offsetX` and `offsetY` functions to set offsets ensures that the apple tree remains centered on the canvas regardless of scaling.

---

### Inspiration and Technical Overview

The project is inspired by the natural beauty of tree growth and rainfall, combining static shapes (like circles and lines) with animation effects to bring dynamic life to the composition.  
- **Implementation**: `setInterval` controls timing, animating the growth through element scaling, while raindrops fall by updating their y-position within `drawElements`.

---

### Code Explanation

1. **Growth Animation**: Within the `startGrowth` function, the `shrinkFactor` gradually increases, creating a smooth transition from a smaller to a full-size tree structure.
2. **Raindrop Animation**: Raindrops are generated periodically, with their downward movement controlled by the `move` function. Raindrops disappear when they leave the canvas to maintain visual clarity.
3. **Adjustable Scale Factor**: The `scaleFactor` dynamically adjusts to window size, ensuring the canvas and graphics display proportionately on any screen.
4. **Overall Scaling of the Apple Tree**: Offset values (`offsetX` and `offsetY`) ensure the tree remains centered on the canvas at all times.

---

## Additional Tools and Methods

This project utilizes the p5.js library and content provided in class. Additionally, to enhance the project and improve its visual quality, I referenced external video tutorials. These tutorials covered topics such as overall tree scaling, raindrop creation, and animation techniques, allowing me to expand and refine the project’s features.

--- 

### Resources

- [Growth Animation Tutorial](https://youtu.be/lMJmtlp6Yus)
- [Rain Effect Tutorial](https://www.youtube.com/watch?v=KkyIDI6rQJI)
- [setInterval Function Documentation](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval)



