Number Jackpot 


Number jackpot game where players click on randomly changing numbers to score points. Test your reflexes and timing in this exciting browser-based game!

🎮 Game Description


Number Jackpot is an interactive web game featuring randomly alternating numbers that players must click to capture and score points. The game combines quick reflexes with strategic timing, all wrapped in a nostalgic Mega Man theme with character-based number styling.

🚀 Features

    Dynamic Number Display: Numbers change randomly at customizable intervals



    Bonus Scoring System: Earn extra points for matching numbers


    Responsive Design: Works seamlessly on desktop and mobile devices


    Time-based Challenge: Limited time to capture each number


    Multiple Attempts: Three attempts per game session


🛠️ Technical Details
Game Configuration

    Speed Control: Modify the speed variable in Number_JACKPOT.js to adjust number rotation speed:

    javascript

var speed = 500; // Default speed in milliseconds


    Lower values = Faster rotation = More challenging


    Higher values = Slower rotation = Easier gameplay


    Recommended minimum: 400ms (below this, CSS transitions may affect number visibility)


Number of Elements: Easily add more number slots by:


    Adding new div elements in HTML:


html

<div onclick="stopthis('aleatorio4')" name="aleatorio4" id="aleatorio4"></div>
<div onclick="stopthis('aleatorio5')" name="aleatorio5" id="aleatorio5"></div>

    Updating the tentativa variable in JavaScript to match the number of elements:


javascript

let tentativa = 5; // Match number of aleatorio divs


Game Mechanics


    Scoring: Sum of captured numbers + bonus points


    Bonus System:


        2 matching numbers: Base score


        3 matching numbers: 2x multiplier


        4 matching numbers: 4x multiplier


        5 matching numbers: 5x multiplier


    Time Limit: 100-second countdown per game session


🎯 How to Play


    Start: Numbers begin rotating automatically when the page loads



    Click: Click on any number to capture its current value



    Score: Each captured number adds to your total score



    Strategy: Wait for high numbers or try to match numbers for bonus points



    Limit: You have 3 attempts (clicks) per game



    Time: Complete your selections before the timer runs out



📁 Project Structure


text

Number_Jackpot/
├── Number_JACKPOT.js      # Main game logic
├── Number_JACKPOT.html    # Game interface
├── NumberJackpot.css      # Styling and responsive design
├── imagens/               # Character images and assets
└── css/                   # Font Awesome and additional styles

🌐 Live Demo

Check out the live version on CodePen:  https://codepen.io/flavioteixeira1/full/vEGeRLv


🎨 Customization
Adding More Number Slots


    Add HTML elements for new slots


    Update the tentativa variable to match the count


    The game automatically handles the new elements


Adjusting Difficulty


    Easy: Set speed = 800 or higher


    Medium: Set speed = 500-700


    Hard: Set speed = 400-500


Theme Modifications


    Modify color schemes in the CSS switch statement


    Replace character images in the imagens/ folder


    Update number styling in the aux_randomico function


🐛 Known Issues


    Very low speed values (<400ms) may cause visual flickering


    Mobile devices may have slightly different timing


    Some older browsers may not support all CSS transitions]


🔧 Browser Compatibility


    Chrome 60+

    Firefox 55+

    Safari 12+

    Edge 79+

📝 License


This project is open source and available under the MIT License.

🤝 Contributing


Contributions, issues, and feature requests are welcome! Feel free to check issues page if you want to contribute.

👨‍💻 Author


Flávio Teixeira


    GitHub: @flavioteixeira1

    Project Repository: Number Jackpot

Pro Tip: For the best gaming experience, keep the speed between 400-800ms and consider adding more number slots for increased challenge!



view in codepen:   https://codepen.io/flavioteixeira1/full/vEGeRLv


