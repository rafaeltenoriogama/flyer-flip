# Flyer with flip animation

Flyer-Flip is an interactive image carousel implemented with HTML, CSS, and JavaScript. The project includes a scrolling animation and an intermittent GIF to guide users. This repository contains the necessary files to set up and run the carousel.
![Cover image](./assets/imgs/readme.png)
## Project Structure

```plantext
Flyer-Flip
├── README.md
├── index.html
└── assets
    ├── css
    │   └── style.css
    └── imgs
        ├── 12.png
        ├── 13.png
        ├── 14.png
        ├── 15.png
        ├── 16.png
        ├── 17.png
        ├── 18.png
        ├── 19.png
        └── 20.png
```
### Contents

##### **index.html**
The index.html file contains the main structure of the carousel. It includes HTML elements for each slide and navigation links. The code is detailed with comments for easy understanding.

##### **style.css**
The style.css file contains the style rules for the carousel. Here are some of the main styles used:

``@keyframes`` ***tonext:*** Defines the animation to move to the next slide.

``@keyframes`` ***tostart:*** Defines the animation to return to the start of the carousel.

``@keyframes`` ***snap***: Controls the scroll snap alignment during animations.

``Body:`` Defines the maximum width, margin, and padding of the document body, as well as the font family and background color.

``@media (max-width:600px):`` Adjusts the height of slides and images for smaller screens.

``carousel:`` Defines the position, height, and main styles of the carousel.

``carousel__viewport:`` Controls the scrolling behavior and alignment of the carousel.

``carousel__slide:`` Defines the appearance and behavior of each slide.

``carousel__snapper:`` Defines how each slide behaves during scrolling.

``assets/imgs``
This folder contains all the images used in the carousel, numbered from 12 to 20.

#### Features
- **Interactive Carousel**: Allows users to navigate between different slides with navigation links.
- **Animated GIF**: Displays a GIF to guide users on how to use the carousel, appearing every 15 seconds.
- **Responsiveness:** The carousel automatically adjusts for smaller screens.

#### Usage
**Clone** the repository:

```bash
git clone https://github.com/your-username/Flyer-Flip.git
Navigate to the project directory:
```
```bash
cd Flyer-Flip
Open the index.html file in your preferred web browser.
```

###### Contribution
If you would like to contribute to this project, feel free to open a pull request. Please ensure your contributions are well-documented and follow the existing code style.

License
This project is licensed under the MIT License.