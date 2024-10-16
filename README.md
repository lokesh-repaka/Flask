

# Flask Learning Project

This project is designed to explore the fundamentals of Flask while implementing a small web application. The aim is to practice key concepts of Flask, such as routing, templates, and handling both GET and POST requests. 


## Key Concepts Covered

### 1. **WSGI (Web Server Gateway Interface)**
   - Flask operates as a WSGI application framework. This project helps understand the fundamental concept of WSGI and how Flask manages request-response cycles.

### 2. **Routing**
   - Several routes are defined in this project to handle requests and return appropriate views. For example, `index.html` is served at the root, and other templates are mapped to different routes.

### 3. **Jinja Templating**
   - Jinja2 templates are used extensively in this project to render dynamic content. You can find templates such as `form.html` and `getresult.html`, which display data based on user inputs or responses from GET/POST requests.

### 4. **GET and POST Methods**
   - The `getpost.py` script demonstrates how Flask handles HTTP GET and POST requests. The `form.html` allows users to submit data, and the results are processed and shown using `result.html`.

### 5. **Serving Static Files**
   - CSS styling for the web pages is handled via the `style.css` file located in the `/static/css` directory, demonstrating how to manage static content in a Flask app.

### 6. **API Handling**
   - The `api.py` file provides insights into setting up and handling basic API endpoints in Flask, using JSON data for processing and responses.


## Project Structure

```
/FLASK
│
├── /static
│   └── /css
│       └── style.css               # Custom styling for the application
│
├── /templates                      # Directory for HTML templates
│   ├── about.html                  # About page template
│   ├── form.html                   # Form to capture POST data
│   ├── getresult.html              # Template to display GET request results
│   ├── index.html                  # Home page template
│   ├── result.html                 # Displays result for form submission
│   └── result1.html                # Additional result page for form handling
│
├── api.py                          # API endpoint handling script
├── app.py                          # Main Flask application entry point
├── getpost.py                      # Handling GET and POST requests
├── jinja.py                        # Jinja templating examples
├── main.py                         # Another Flask entry script
├── sample.json                     # Sample data file for JSON manipulation
```

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <your-github-repo-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd FLASK
   ```
3. Install dependencies:
   ```bash
   pip install Flask
   ```
4. Run the Flask application:
   ```bash
   python app.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/` to view the app.

## Future Enhancements
- Implement form validation using Flask-WTF.
- Add database integration with SQLAlchemy.
- Expand error handling and custom error pages.
