# GTA VI-Inspired Promotional Website

## 1. Project Theme
This project is a multi-page promotional website inspired by the Grand Theft Auto VI marketing aesthetic. It focuses on immersive layouts, vibrant media presentation, full-screen canvas scroll animations, and a sleek, responsive dark-mode design. The overarching theme highlights the fictional state of Leonida, Vice City, and protagonists Jason and Lucia.

## 2. Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript (utilized for scroll-scrubbing canvas animations, responsive menu toggling, and video overlay functionality)

## 3. Website Pages

### Home Page — `index.html`
Introduces the game with a bold hero section, a launch trailer video modal, pre-order call-to-actions, and interactive scroll-driven canvas animations.

### Gallery Page — `gallery.html`
Presents a visual archive of selected artwork, wallpapers, and character portraits featuring the people and places of Leonida.

### Music Page — `music.html`
Highlights the sounds of Leonida by featuring a grid of in-game radio stations, such as Cocoteo and Flash FM, alongside links to the official album.

## 4. Project Structure
- `index.html` — The main landing page
- `gallery.html` — The artwork and wallpapers gallery
- `music.html` — The radio stations and music showcase
- `styles.css` — Core website styling for the home page
- `media-pages.css` — Shared styling specifically tailored for the Gallery and Music pages
- `frames/` & `frames2/` — Directories containing the sequential image frames for the canvas scroll animations
- `README.md` — Project documentation

## 5. AI Usage Log
AI assistance was used during development, bug fixing, and functionality optimization. The following entries describe the types of assistance requested:

| Task | AI Assistance Requested | How the Assistance Was Used |
|---|---|---|
| **Global Responsiveness** | Help making the whole website responsive. | Used to rewrite and condense CSS media queries (using fluid `clamp()` functions) to ensure the entire website scales flawlessly across all device sizes. |
| **Interactive JavaScript** | Help with scroll-scrubbing canvas animations and responsive menu toggling. | Used to structure and refine the Vanilla JavaScript required for the scroll-bound image sequences and the mobile hamburger menu interactions. |
| **Video Overlay Modal** | Help implementing and styling the video overlay. | Used to build and troubleshoot the CSS and layout logic for the launch trailer pop-up modal, ensuring it displays correctly over the page content. |

## 6. How to Run the Project
1. Clone or download the project folder to your local machine.
2. Open `index.html` in any modern web browser.
3. Use the top navigation links or the hamburger menu overlay to visit the Gallery and Music pages.

## 7. Customization
- Edit the HTML files to update text, release dates, and trailer embed links.
- Edit `styles.css` and `media-pages.css` to change the global layout, colors, and font families.
- To customize the scroll animations, replace the `.jpg` sequence files in the `frames/` and `frames2/` folders and adjust the `frameCount` variable in the `index.html` script.

## 8. Notes
- Ensure all static images, such as `launch-image.png` and `gta6-logo.png`, are placed in the correct directory relative to the HTML files.
- The newsletter subscription form in the footer is for visual presentation only and requires external backend integration to process submissions.
- The canvas scroll animation strictly requires sequential images named in the format `frame_001.jpg`, `frame_002.jpg`, etc., to render correctly on scroll.