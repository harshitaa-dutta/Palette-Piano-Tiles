# Palette Piano Tiles

**Palette Piano Tiles** is an interactive web application designed using musical octaves. It allows users to create and interact with an `n x n` matrix based on their input. Users can hover over the tiles in the matrix to play musical notes, with each tile generating a unique and random note until all notes are played once. The sequence then repeats on subsequent hovers. The audio playback is visually accompanied by dynamic color changes on the tiles.

---

## Features

- **Dynamic Matrix Creation**: Users input the desired matrix size (`n`), and an `n x n` grid is generated.  
- **Interactive Tiles**: Hovering over a tile triggers:
  - A random musical note (from an octave of 8 notes).  
  - A unique color change, enhancing the visual experience.  
- **Sequential Notes**: Notes play in order, looping back to the start after all have been played.  
- **Reset Interaction**: Pressing the "Enter" key clears the colors from all hovered tiles.

---

## Roadmap

1. **User Input**: The first page accepts the matrix size (`n`) as input.  
2. **Matrix Generation**: An `n x n` matrix is created dynamically based on the user's input.  
3. **Musical Interaction**:  
   - The 8 musical notes play sequentially based on indices ranging from 0 to 7.  
   - The sequence restarts at index 0 after reaching 7, ensuring continuous play.  
4. **Visual Feedback**: Tiles change to random colors when hovered over, enhancing interactivity and engagement.

---

## Technologies Used

The webpage is built with **HTML**, **CSS**, and **JavaScript**.

### HTML:
- Utilized `<form>` elements to handle user input and define data submission behavior.  
- Animated "GO" button and placeholders for improved user experience.

### CSS:
- **Title Styling**: Each tile is styled with hover effects and shadows.  
- **Button Animation**:  
  - Animated the "GO" button using a `transition` effect with a duration of 0.3 seconds.  
  - Border changes upon hover.  
- **Placeholder Animation**: Placeholders are auto-animated using a `transition` effect of 0.4 seconds.

### JavaScript:
- **Tile Colors**: Random colors are assigned to tiles using the `Math.random()` function.  
- **Audio Playback**: Musical notes are played on hover, based on sequential indices.  
- **Reset Functionality**: Pressing "Enter" clears the colors from all hovered tiles.  
- **Mouse Interaction**: Used `mouseover` events to trigger color and audio changes.

---

## Deployment

This project is deployed and accessible online. Visit:  

[Palette Piano Tiles - Tiles and Waves](https://harshitaa-dutta.github.io/Palette-Piano-Tiles/)

---
