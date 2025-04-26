# Jacob Vallery - Bellarmine University - Capstone 
# CS-450-ON

# Capstone : DinnerWizard 
This Application runs on Docker with Node.js.
Verify both are downloaded to your system to ensure this application runs correctly. 

Once this repository is successfully cloned, navigate to the corresponding (destination) directory in your terminal. 

Ensure the current working directory is within the application folder. (RUN cd application)

&nbsp;&#10028;&nbsp;&nbsp;RUN docker build -t dinner_wizard .

Make sure to include the '.' after 'dinner_wizard' above.

&nbsp;&#10028;&nbsp;&nbsp;RUN docker run -p 3000:3000 dinner_wizard

This will run the app on your local machine at http://localhost:3000

Navigate to http://localhost:3000 on your browser to enjoy DinnerWizard! &#9770;
