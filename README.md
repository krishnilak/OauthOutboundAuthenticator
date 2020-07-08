# OauthOutboundAuthenticator

1. Build the project using
mvn clean install

2. Copy the JAR file inside target folder to the IS dropins folder
from: <Project_Home>/target
to: <IS_home>/repository/components/dropins

3. Start IS

4. In the management console, Expand Main>Identity>Identity providers and try to add a identity provider
Under federated Authenticators now "OAUTH2 Configuration" is visible

5. Configure Oauth2 and start using
