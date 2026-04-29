# Scratch Coding Practice 101  
## Project 5 of 10 — HTML Video Player (freeCodeCamp)

**Live Project:** [https://sharmaankita3387.github.io/fccHTMLWebsitePractice05/](https://sharmaankita3387.github.io/fccHTMLWebsitePractice05/)  

---

## About This Project  
This is Project 5 in my coding practice series. In this project, I focused on working with the HTML `<video>` element to embed and control video content within a web page.

I built a simple video player that supports multiple file formats to ensure compatibility across different browsers.

---

## Guiding Principle

> "To become a reliable VibeCoder, you must first understand what’s happening behind the scenes as a Software Engineer."

---

## Key Concepts Practiced
- Embedding video using the `<video>` element  
- Using attributes like `controls`, `loop`, `muted`, and `poster`  
- Providing multiple video formats (`mp4`, `webm`, `ogg`, `mov`) for browser support  
- Structuring media content with fallback sources  

---

## Code Example
```html
<video width="640" loop controls muted poster="https://cdn.freecodecamp.org/curriculum/labs/past-event2.jpg">
  <source src="https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.mp4" type="video/mp4">
</video>
