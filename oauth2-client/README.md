oauth-client
========

A demo and helper class for providing Google OAuth2 authentication in java.

Prerequisites

- Google API access credentials (Client ID, Client Secret). Set it up here https://code.google.com/apis/console/
- Set up allowed Redirect URIs at Google API -> API Access. Input: http://localhost:8080/oauth2-client/index.jsp

Usage

1. Download client_secrets.json from https://console.developers.google.com/apis/credentials
2. Compile the project ($ mvn clean install)
3. Deploy war to application server
4. Browse to: http://localhost:8080/oauth2-client/
5. Click "log in with google" on top of this page
