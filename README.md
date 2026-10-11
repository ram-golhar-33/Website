# RAM Foundation — Creating Hope, Changing Lives

A modern, responsive social service organization website built using HTML5 and CSS3. RAM Foundation showcases community development initiatives, education, healthcare, environmental protection, humanitarian support, and volunteer opportunities.

## Project Overview

RAM Foundation is a frontend website project designed to present a nonprofit organization in a professional and engaging way. It features a modern user interface, responsive layouts, smooth scrolling, interactive hover effects, and visually appealing sections.

## Features

- **Modern UI:** Clean design with a professional teal color palette.
- **Responsive Design:** Layouts optimized for desktop, tablet, and mobile screens.
- **Navigation Bar:** Quick navigation between website sections.
- **Hero Section:** Introduction to the foundation and its mission.
- **About Us:** Organization overview and mission statement.
- **Our Services:** Education, healthcare, community development, environmental protection, humanitarian support, and skill development.
- **Impact Statistics:** Dedicated section for showcasing organizational achievements.
- **Projects Gallery:** Visual presentation of community initiatives.
- **Volunteer Call to Action:** Encourages visitors to participate.
- **Contact Link:** Email-based contact action.
- **CSS Animations:** Hover transitions, image effects, and smooth scrolling.
- **SEO Basics:** Page title, description, and semantic HTML elements.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts, responsive design, and animations |
| Google Fonts | Inter and Playfair Display typography |
| Unsplash | Website photography |
| Flexbox | Navigation and flexible layouts |
| CSS Grid | Service cards, projects, statistics, and footer layouts |
| Media Queries | Responsive design for different screen sizes |

## Project Structure

```text
RAM-Foundation/
├── index.html
├── style.css
└── README.md
```

- `index.html` — Contains the website structure and, in the original version, embedded CSS.
- `style.css` — Contains the optional separate stylesheet with gradient backgrounds, glassmorphism, reusable components, and responsive styling.
- `README.md` — Project documentation.

**Note:** The original HTML includes its own CSS inside a `<style>` element. If you use the separate `style.css` file, link it inside the HTML `<head>` using:

```html
<link rel="stylesheet" href="style.css">
```

To avoid conflicting styles, remove or consolidate duplicate CSS rules when combining the two stylesheets.

## Website Sections

### 1. Home
Introduces RAM Foundation with a full-screen hero image, mission statement, and navigation buttons.

### 2. About Us
Explains the foundation's mission and its focus on empowering communities.

### 3. Our Work
Highlights key service areas:
- Education and skill development
- Healthcare and well-being
- Community development
- Environmental protection
- Humanitarian support

### 4. Our Impact
Displays statistics cards for people supported, community projects, volunteers, and communities reached.

### 5. Projects
Showcases sample initiatives focused on education, healthcare, and environmental awareness.

### 6. Get Involved
Encourages visitors to volunteer, support initiatives, and contact the organization.

### 7. Footer
Provides organizational navigation, involvement links, social media placeholders, and copyright information.

## How to Run the Project Locally

### Step 1: Clone the repository

```bash
git clone https://github.com/<YOUR-GITHUB-USERNAME>/<YOUR-REPOSITORY-NAME>.git
```

### Step 2: Navigate to the project directory

```bash
cd <YOUR-REPOSITORY-NAME>
```

### Step 3: Open the website

Open `index.html` in your browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension for local development.

No backend, database, package installation, or build process is required for the current static website.

## Customization

You can customize the website by:

- Replacing the sample images with your own photographs.
- Updating the organization name, mission, and service descriptions.
- Adding real contact information and verified social media links.
- Adjusting colors, typography, spacing, and responsive layouts in CSS.
- Connecting a backend or contact form service if form submissions are required.

## Deployment Options

This static website can be hosted using:

- GitHub Pages
- Amazon S3 static website hosting with an appropriate public-access or CloudFront configuration
- Amazon EC2 with Nginx
- Netlify
- Vercel

For an AWS portfolio project, deploying the website on an EC2 Ubuntu instance with Nginx is a useful way to practice Linux administration, web server configuration, networking, and cloud hosting.

## Future Enhancements

- Add a functional volunteer registration form.
- Integrate a secure donation platform.
- Add a backend API and database for contact submissions.
- Create an administration dashboard for managing projects.
- Add accessibility improvements and performance optimization.
- Configure a custom domain and HTTPS.
- Add analytics and a content management workflow.

## Important Notes

- The impact statistics and organizational claims shown in the sample design are placeholder content. Replace them with verified information before publishing.
- The email address `contact@ramfoundation.org` is a sample contact address and should be verified before use.
- Social media links are placeholders until actual organization profiles are provided.
- Images and Google Fonts are loaded from external services, so an internet connection is required for those resources.
- This project is a frontend demonstration. Donation processing, volunteer registration, and backend functionality are not implemented.

## Author

**Ram Golhar**

GitHub: [ram-golhar-33](https://github.com/ram-golhar-33)

## License

This project is intended for learning and portfolio demonstration. Add a `LICENSE` file if you want to grant others explicit permission to reuse, modify, or distribute the code.

---

**RAM Foundation — Creating Hope. Changing Lives.**
