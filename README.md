# SDKSamples
Prerequisites

Before you begin, ensure that you have the following prerequisites in place:

Node.js and npm (Node Package Manager) installed on your system.
An Okta developer account with an Okta application set up for Email Magic Link authentication. Refer to Okta's Email Magic Link Guide for detailed instructions.

**Step 1: Clone the Repository**

Start by cloning the Okta Auth JS SDK sample repository to your local machine. Open your terminal and run the following command:

**Code:**
git clone https://github.com/okta/okta-auth-js.git
Navigate to the express-embedded-auth-with-sdk sample:
cd okta-auth-js/samples/generated/express-embedded-auth-with-sdk

**Step 2: Configure Your Environment**

Create a .env file in the root directory of the project to store your Okta configuration values. You can copy the .env.template file and fill in the appropriate values.
**Code:**
cp .env.template .env
Edit the .env file and replace the placeholders with your Okta application details:

OKTA_ORG_URL=https://your-okta-domain
OKTA_CLIENT_ID=your-okta-client-id
OKTA_CLIENT_SECRET=your-okta-client-secret

**Step 3: Install Dependencies**

Install the project dependencies using npm:

**Code:**
npm install

**Step 4: Start the Application**

Start the Express.js application:

**Code:**
npm start
Your Okta Email Magic Link authentication integration should now be running locally.

**Step 5: Test the Integration**

Open your web browser and visit http://localhost:3000. You should see the sample application running.

Click the "Login with Okta" button to initiate the Okta authentication process.
You will be redirected to Okta's authentication flow, where you can enter your email address.
An email containing a magic link will be sent to your email address.
Click the magic link in the email to complete the authentication process and be logged in to the sample application.
Conclusion

You have successfully integrated Okta Email Magic Link authentication using the Okta Auth JS SDK and the provided sample application. You can now customize this sample to fit your specific use case or integrate it into your own
