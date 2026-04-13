## Flask Clean Blog Website

This project is a multi-page blog website built using Flask and the Clean Blog Bootstrap template.

The application demonstrates how Flask can be used to serve multiple pages while maintaining reusable layout components such as a shared header and footer using template includes.

The project includes pages for Home, About, Contact, and blog posts rendered through Flask routes.

This project was built as part of the #90DaysOfCode challenge to practice backend routing, template reuse, and structured web application development using Flask.

---

## Technologies Used

Python  
Flask  
HTML5  
CSS3  
Bootstrap  
Jinja2 Templating  

---

## Key Concepts Demonstrated

Flask routing for multi-page applications

Template rendering using render_template

Reusable layout components using Jinja template includes

Serving static files such as CSS, JavaScript, and images

Responsive layouts using Bootstrap

Organizing frontend assets and backend logic in a scalable project structure

---

## Project Structure

```
project/
│
├── main.py
│
├── templates/
│   ├── header.html
│   ├── footer.html
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   └── post.html
│
├── static/
│   ├── assets/
│   │   ├── favicon.ico
│   │   └── img/
│   │       ├── about-bg.jpg
│   │       ├── contact-bg.jpg
│   │       ├── home-bg.jpg
│   │       ├── post-bg.jpg
│   │       └── post-sample-image.jpg
│   │
│   ├── css/
│   │   └── styles.css
│   │
│   └── js/
│       └── scripts.js
```

---

## Application Workflow

1. Flask initializes the web server
2. The homepage route renders the main blog page
3. Additional routes serve the About and Contact pages
4. Shared layout components are included using Jinja templates
5. Static assets such as CSS, images, and JavaScript are served from the static folder

---

## Installation

Install Flask

```
pip install flask
```

---

## Run

```
python main.py
```

Open your browser and navigate to

```
http://127.0.0.1:5000
```

---

## Why This Project Matters

This project demonstrates how backend frameworks can structure multi-page web applications while maintaining reusable UI components and organized static assets.

It reflects how real-world Flask applications integrate backend routing with frontend templates.

---

## Author

Faiz Hasan  
Python Automation & Backend Developer
