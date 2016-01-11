# Environment indicator

Set of tools which brings the environment name information to Drupal.

## Installation

Download and activate the module. You may use composer to download.

## What does it do ?

This is more or less useless as of now, but the modules does:

 *  Reads the *current_env* variable and set the *ENVI_ENV* constant with its value
 *  Sets the *ENVI_ENV* to *(unknown)* if the variable is not set
 *  Adds the *X-Drupal-Environment* header in source to all sent mail with the constant value

## Future plans

 *  Do more stuff
 *  Append in HTML page a debug bar containing the environment name

Yep, that's pretty much everything...
