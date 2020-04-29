# Bluegreen Deployments
Simple demo code for Blue Green Deployments

# Set to blue

Using an env var; set the application to display a `blue` square

`oc env dc/bluegreen COLOR=blue`

# Set to green

Same as you did above; set it to a `green` square with

`oc env dc/bluegreen COLOR=green`

# Note

The app defaults to `blue` unless you set it to green. Any other string or empty `COLOR` var will default the square to `blue`

# Checking Zapier email notification 
# Whenever any commit is done in this repository an email is sent to vrvenky.1470@gmail.com from vrvenky.1407@gmail.com 
# 
