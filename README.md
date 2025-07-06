🌐 Flask Portfolio Website  
A clean and responsive personal portfolio website built using Python and Flask. Perfect for showcasing your skills, projects, and education — with a functional contact form for leads or collaboration.

📌 Features  
✅ Dynamic portfolio using Flask and Jinja2 templating  
✅ Clean homepage with objective, skills, education, and certifications  
✅ Contact form with flash message feedback  
✅ Mobile-friendly layout with modern CSS  
✅ Easy to expand: Add blogs, projects, or resume pages

⚙️ How It Works  
1. Flask handles routing and rendering HTML templates  
2. Pages are styled with custom CSS (located in static/css)  
3. Contact form sends POST data and triggers a thank-you flash  
4. Content is modular and editable in the `templates/` folder

🚀 Getting Started

1. Clone the Repository  
   git clone https://github.com/your-username/flask-portfolio-site.git  
   cd flask-portfolio-site

2. Create a Virtual Environment (Optional but recommended)  
   python -m venv venv  
   On Windows: `venv\Scripts\activate`  
   On macOS/Linux: `source venv/bin/activate`

3. Install Dependencies  
   pip install -r requirements.txt

4. Run the App  
   python app.py

🔗 Visit  
After launching, open your browser and go to:  
http://127.0.0.1:5000/

📁 Project Structure

portfolio_site/
├── app.py                  - Main Flask app  
├── requirements.txt        - Flask dependency  
├── static/  
│   └── css/  
│       └── styles.css      - Styling rules  
└── templates/  
    ├── base.html           - Reusable layout  
    ├── index.html          - Portfolio content  
    └── contact.html        - Contact form



Created by Muzakkir Sakharkar – 2025
