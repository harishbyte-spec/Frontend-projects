Overview
The challenge
Users should be able to:

View a responsive profile card layout

See hover and active states for the social links on desktop

View a mobile-optimized version with hover interactions disabled

Screenshot
📸 Replace the image path below once you've added your screenshot

### Screenshot

![Screenshot](./assets/images/web%20view.jpg) ----- WEB VIEW

![Screenshot](./assets/images/mobile%20view.jpg) ----- MOBILE VIEW

Links
Solution URL  :

Live Site URL :

My process
Built with
Semantic HTML5

CSS custom properties

Flexbox layout

Mobile-first design

Google Fonts (Inter)

Media queries for responsive behavior

What I learned
How to use flex to center items both vertically and horizontally.

Proper use of :hover with media queries to disable it on touch devices.

Improved understanding of mobile-first responsive design strategy.

css
Copy
Edit
@media (min-width: 722px) {
  .social_box:hover {
    background-color: #a5c63b;
    color: black;
  }
}
Continued development
Add a tags to make each social box link to a real profile.

Introduce animations or Framer Motion for smoother interactivity.

Improve accessibility with aria-labels and better keyboard navigation.

Useful resources
MDN Web Docs – Flexbox

CSS Tricks – Responsive Design

Frontend Mentor Discord Community

Author
GitHub – @harishbyte-spec

Frontend Mentor – @harishbyte-spec