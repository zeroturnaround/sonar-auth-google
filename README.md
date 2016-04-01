# sonar-auth-google
Google Authentication for SonarQube

Forked from https://github.com/SonarSource/sonar-auth-github

Uses Google OAuth2 and Google API (oauth2.info) to sign in users.

Configuration in sonar.properties:

sonar.auth.google.clientId=Google ClientID

sonar.auth.google.secret=Google Client Secret

sonar.auth.google.hd=Optional Hosted Domain

sonar.auth.google.enabled=true

sonar.auth.google.allowUsersToSignUp=true

NB! In Google auth configuration allow the callback url

protocol://your-host-path/oauth2/callback/google

Eg. https://my-domain/mySonar/oauth2/callback/google