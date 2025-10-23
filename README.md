**Analog Watch – Web Application**



This project is a simple Analog Watch UI built using HTML, CSS, and JavaScript. The watch dynamically updates every second to show the current time in an analog style.

It demonstrates:


HTML structure for rendering.

CSS for styling and positioning.

JavaScript logic for drawing and updating the clock hands in real time.

**📂 Project Structure**

    project-root/
    │
    ├── index.html      # Main HTML file with clock UI and logic
    ├── README.md       # Documentation

**⚙️ How It Works**

HTML provides the structure and links JavaScript.

CSS applies background, font, and clock container styling.

JavaScript:

Uses the canvas API for drawing.

Draws clock ticks (hours & minutes).

Calculates hour, minute, and second hand positions based on system time.

Updates the UI every second using setInterval().

**🔄 Workflow**

The page loads → Browser executes index.html.

A styled circular clock face is created with ticks and shadows.

JavaScript retrieves the current time using Date().

The hour, minute, and second hands are drawn using trigonometric calculations (sin & cos).

The clock is updated every second.

**🚀 How to Run**

Clone or download the project.

    git clone <repo-url>
    cd project-root


    Open index.html in any modern browser.

    You’ll see a live Analog Watch running in the center of the page.

**🖼️ Features**

    Real-time analog clock with second, minute, and hour hands.
    Color-coded hands for better visibility:

    Hour hand → Dark blue

    Minute hand → Green

    Second hand → Red

    Decorative ticks and shadows for a polished look.

    Fully responsive canvas-based rendering.

**🛠️ Technologies Used**

    HTML5 – Page structure

    CSS3 – Styling and layout

    JavaScript (ES6) – Clock logic and drawing

    Canvas 2D API – Rendering the watch UI

**📌 Notes**

    The clock runs entirely on the client-side (no backend needed).

    Works on all modern browsers.

    You can customize colors, sizes, and styles by modifying the CSS and JS values.
