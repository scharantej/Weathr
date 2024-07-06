## Building a Weather App Using Python Flask

### HTML Files

- `index.html`: This is the main HTML file that users will interact with. It will contain the front-end components for displaying the weather information and interacting with the app.
  - It will include a form for the user to input the location for which they want to retrieve weather data.
  - It will have a div element to display the weather information once retrieved from the API.

### Routes

- `/`: This route will handle the GET request for the index page.
  - It will render the `index.html` template.
  
- `/weather`: This route will handle the POST request for retrieving weather data.
  - It will extract the location from the request form.
  - It will make an API call to retrieve the weather data for the given location.
  - It will render the `index.html` template, passing the retrieved weather data to the template for display.