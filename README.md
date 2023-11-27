# actions

This is a git action ready to deploy a template to an azure appservice plan. For this to work correctly:
- Create an app service plan.
- Copy the publish profile and add it as a secret to the action repository, then push the changes to trigger git actions.

This App currently exists on my Azure account and whenever I make changes here, and push. Automatic deployment is carried out to azure.

Improvements:
To improve this lab, I will recommend adding confirmation and approval gates and to switch the deployment from push to pull request as this is preferable for a production environment.
