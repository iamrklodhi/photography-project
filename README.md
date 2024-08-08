<h1>>Photography Landing Page</h1>
This repository contains the source code for a photography landing page. The page uses an image (photo.jpg) and a custom CSS style sheet (style.css) to create a visually appealing user interface.

Table of Contents
Overview
Features
Installation
Usage
Contributing
License
Overview
This project is a simple landing page for photographers or photography enthusiasts. It showcases a background image and a sidebar menu with links to various sections.

Features
Full-screen Background Image: The main section of the page is covered by a full-screen background image.
Sidebar Menu: A slide-in sidebar menu with navigation links.
Responsive Design: The layout is designed to be responsive and looks good on various screen sizes.
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/photography-landing-page.git
cd photography-landing-page
Open the project:
Open the index.html file in your preferred web browser to see the landing page.

Usage
Background Image: The photo.jpg file is used as the background image. You can replace this image with your own by updating the style.css file.
Customizing Styles: Modify the style.css file to change the appearance of the page. The main CSS classes are explained below:
CSS Classes
.main_box: Sets the background image and covers the entire viewport height.
.btn_one i: Styles for the menu button icon.
.sidebar_menu: Styles for the sidebar menu, including its position, size, and transition effects.
.sidebar_menu .logo: Styles for the logo within the sidebar.
.sidebar_menu .menu: Styles for the menu items within the sidebar.
.sidebar_menu .social_media: Styles for the social media icons within the sidebar.
Example
Here is a brief example of how you can add a new menu item in the sidebar:

html
Copy code
<li><i class="icon-class"></i><a href="#new-section">New Section</a></li>
Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
