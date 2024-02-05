Getting Started
IMPORTANT: Do not send pull requests to this repository. This is a template repository and is not used for grading. Any pull requests will be closed and ignored.

Introduction
This simple Stripe Payment Application allows you to integrate with the Stripe payment processing service. Follow the steps below to set up and run the application locally.

Setup
Pre-requisities
To run the application you would require:

Java
Temporal
Docker
Stripe API Keys

Stripe API Keys
Sign up for a Stripe account and get your API keys from the Stripe Dashboard. Then in application.properties file add the following line with your secret key.

stripe.api-key=sk_test_51J3j

Run the Application

Open your browser:
Navigate to http://localhost:8080.

Fill out the form:
Enter the user's name and email in the provided form.

Submit the form:
Trigger the Stripe payment process by submitting the form.

View Stripe Dashboard:
Log in to your Stripe Dashboard:
Access your Stripe account.

Check payment information:
In the Dashboard, you should see information related to the payments made using the application.

Additional Notes:
Make sure your Stripe account is in test mode, and you are using test API keys.
This application is for educational purposes and uses a simplified setup.
