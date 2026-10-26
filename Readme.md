# Digital Marketing Agency Website

A modern, responsive static website for a digital marketing agency, built using HTML, CSS, and JavaScript. The website is designed to showcase digital marketing services, highlight the agency's expertise, and help potential clients learn more about its offerings.

## Features

- **Responsive Design:** Adapts to desktop, tablet, and mobile screens.
- **Services Showcase:** Displays digital marketing services and solutions.
- **Modern User Interface:** Clean layout with attractive styling and easy navigation.
- **Interactive Elements:** JavaScript-powered functionality for an engaging user experience.
- **Business Information:** Sections for agency details, services, and contact information.
- **Static Website:** Fast and lightweight, with no backend or database required.

## Technologies Used

- **HTML5** – Structures the website content.
- **CSS3** – Handles styling, layouts, and responsive design.
- **JavaScript** – Adds client-side interactivity.
- **Nginx Alpine** – Serves the static website through a lightweight Docker container.
- **Docker** – Packages the website for consistent deployment and testing.

## Project Structure

```text
devops-project/
├── Dockerfile
├── index.html
├── README.md
├── style.css
├── script.js
└── images/
```

*Note: Update the file and folder names above to match your actual project structure.*

## Run Locally

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd "devops project"
   ```

3. Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

## Run with Docker

### Prerequisites

- Docker Desktop installed and running.
- A working Docker Engine.

### Build the Docker Image

Run this command from the project root directory:

```bash
docker build -t digital-marketing-agency .
```

### Start the Container

```bash
docker run -d --name digital-marketing-agency-container -p 8080:80 digital-marketing-agency
```

### Access the Website

Open the following URL in your browser:

http://localhost:8080

### Check the Running Container

```bash
docker ps
```

### Stop the Container

```bash
docker stop digital-marketing-agency-container
```

### Remove the Container

```bash
docker rm digital-marketing-agency-container
```

## Deployment

The website can be deployed using static hosting platforms such as GitHub Pages or served through an Nginx Docker container on a cloud server.

## Future Enhancements

- Integrate a functional contact and enquiry form.
- Add client testimonials and case studies.
- Implement SEO improvements and performance optimization.
- Connect a backend for dynamic content and lead management.
- Set up a CI/CD pipeline for automated deployment.

## Author

**Om Shankar**

## License

This project is intended for educational and portfolio purposes. Add an appropriate open-source license if you plan to distribute or reuse the project under specific terms.
