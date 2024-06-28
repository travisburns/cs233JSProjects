# Week 6 Project: Web Development Project: Event Registration Application

This repository showcases an advanced web application for event registration, featuring multiple pages with different functionalities, API integration, and data visualization.

## Project Overview

A comprehensive event registration system with three main components: registration form, status dashboard, and about page.

### 1. [AJAX-Enabled Bookmarker Application](https://github.com/LCC-CIT-Programming-CS233JS/06-event-template-travisburns/blob/master/README.md) - Click Link
  ### (http://citstudent.lanecc.net/~burnst074/CS233JS/Lab6/javascriptMeetup/dist/) - Click Link  
### Key Features:
1. **Registration Page (Home)**
   - User registration form with validation
   - AJAX form submission
   - Real-time form validation using regular expressions

2. **Status Page**
   - Data visualization of registrants' experience and profession
   - Interactive charts using Chart.js
   - AJAX data fetching

3. **About Page**
   - Event information
   - Interactive map integration using Google Maps API

### Technologies Used:
- HTML5, CSS3 (with Bootstrap)
- JavaScript (ES6+)
- Webpack for module bundling
- Babel for JavaScript transpiling
- Chart.js for data visualization
- Google Maps API for location display
- Fetch API for AJAX requests
- JSON Server for mock backend

### Implementation Highlights:
1. **Modular Architecture:**
   - Separate JavaScript files for each page (home.js, status.js, about.js)
   - Shared navigation component across all pages

2. **Advanced Form Validation:**
   - Custom validation using regular expressions
   - Real-time feedback to users

3. **Asynchronous Data Handling:**
   - AJAX for form submission and data retrieval
   - Promise-based API calls using Fetch

4. **Data Visualization:**
   - Dynamic chart generation based on user data
   - Interactive charts for better data interpretation

5. **External API Integration:**
   - Google Maps API for displaying event location
   - Customized map markers and info windows

6. **Responsive Design:**
   - Bootstrap for mobile-friendly layouts
   - Custom CSS for enhanced styling

## Skills Demonstrated
- Advanced JavaScript (ES6+) programming
- Asynchronous programming and Promise handling
- Third-party API integration (Google Maps, Chart.js)
- Data visualization techniques
- Form validation and user input handling
- Modular web application design
- Webpack configuration for development and production
- Environment variable management for API keys

## Project Structure
- `src/`: Source files
  - `js/`: JavaScript files for each page and shared components
  - `css/`: Stylesheets
  - `html/`: HTML templates for each page
- `webpack.config.js`: Webpack configuration
- `package.json`: Project dependencies and scripts

## Setup and Running
1. Clone the repository
2. Run `npm install` to install dependencies
3. Create a `.env` file with necessary API keys
4. Run `npm run build` for production build
5. Use `npm run watch` for development with live reloading

## Future Enhancements
- Implement user authentication
- Add email confirmation for registrations
- Enhance data visualization with more interactive features
- Implement server-side rendering for improved performance

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check the issues page for open problems or suggest new features.

## License
This project is MIT licensed.
