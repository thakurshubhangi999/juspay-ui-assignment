# Juspay UI Assignment

This project is a UI development assignment for **Juspay Technologies Private Limited**. It demonstrates responsive web design and UI component development using React and CSS.

## Prerequisites

Before setting up the project, ensure that you have the following installed:

- **Node.js** (version 18 or later) - [Download Node.js](https://nodejs.org/)
- **npm** (Node Package Manager) or **yarn** (Optional) - npm is included with Node.js
- **Git** - [Download Git](https://git-scm.com/)

## Getting Started

Follow the steps below to set up and run the project locally:

### 1. Clone the repository

Clone the repository to your local machine using Git:

```bash
git clone https://github.com/thakurshubhangi999/juspay-ui-assignment.git
cd juspay-ui-assignment

2. Install dependencies
Once you have cloned the repository, navigate to the project directory and install the required dependencies:
npm install

Or, if you prefer using yarn:
yarn install

3. Run the project locally
To run the project locally, execute the following command:
npm start

Or with yarn:
yarn start

This will start the development server and open the project in your default web browser at http://localhost:3000.

Deployment
The project is deployed on Vercel for easy access and sharing.

You can view the live version of the application at:
**Juspay UI Assignment** - [Live Demo](https://juspay-ui-assignment.vercel.app/)

Folder Structure
Here’s an overview of the project’s folder structure:

├── public/                 # Public assets like index.html, icons, etc.
├── src/                    # Source code for the React application
│   ├── components/         # Reusable React components
│   │   └── UIAssignment.js # The main UIAssignment component
│   │   └── UIAssignment.css # Styles for the UIAssignment component
│   ├── App.js              # Entry point for the application
│   ├── App.css             # Global styles for the app
├── package.json            # NPM package configuration
└── README.md               # This file

Design Decisions, Challenges Faced, and Improvements Made:
1. Design Decisions

Flexbox Layout: The layout is built using Flexbox for easy alignment and responsiveness. Flexbox allows for a more flexible and efficient layout system, especially when working with dynamic content and varying screen sizes.
CSS Grid Overlay: A grid overlay with semi-transparent lines was used as a design element to create a sense of structure. This grid serves a visual purpose and is hidden at lower screen sizes for better readability.
Radial Gradients for Background: A combination of radial gradients with different opacity values was used to create a visually appealing and modern background effect. This design decision aimed to give a vibrant, yet subtle, look to the interface.
Responsive Design: The UI is responsive, with font sizes and layout components adjusting according to screen size. Media queries are used to ensure that the text and layout elements are appropriately sized on different devices, from large screens to mobile devices.

2. Challenges Faced
Responsive Typography: One of the primary challenges was ensuring that the text remained readable across various devices. Initially, the font sizes were too large for smaller screens, making the content look squished or overflowing. This was addressed by using media queries to scale font sizes and adjust padding based on the screen width.
Aligning Components: Positioning the components, particularly the title and subtitle, while ensuring their alignment across different screen sizes was tricky. Flexbox helped to solve this problem by making the layout more adaptive without the need for absolute positioning in most cases.
Complex Background Layouts: Achieving the gradient overlay and grid pattern was tricky initially, as it needed to maintain a balance between the visual design and the performance. Ensuring that the gradients were rendered correctly on all screen sizes without negatively affecting performance was a challenge.

3. Improvements Made
Mobile Responsiveness: Initially, the design was not mobile-friendly, and the layout broke on smaller screens. Media queries were introduced to adjust text sizes and container sizes for devices with screen widths of 1024px, 768px, and 480px.
CSS Optimization: After identifying areas where redundant styles were applied, some CSS properties were refactored to be more efficient. For example, background gradients were applied using shorthand notation to reduce redundancy.
Visual Enhancements: The grid pattern and background overlays were improved for better visual appeal while maintaining a minimalist approach. The opacity of the grid and gradient elements was adjusted to ensure that they did not overpower the main content.
Scalability: The design was made more scalable by using relative units like vw, vh, and % for widths and margins, which makes the design adapt more effectively to different screen sizes.
Styles and Responsiveness
The UIAssignment component uses flexbox for layout and is fully responsive.
Media Queries have been used to ensure that the UI adapts for different screen sizes, from desktops to mobile devices.
The layout consists of a background overlay with radial gradients and a grid pattern for added visual appeal.

Contributing
If you’d like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -am 'Add new feature').
Push your changes (git push origin feature-branch).
Create a pull request.


### Key Update:
- The **deployment link** is now clickable using the markdown syntax `[**Juspay UI Assignment - Live Demo**](https://juspay-ui-assignment.vercel.app/)`.


