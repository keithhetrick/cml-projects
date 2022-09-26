# Command Line Interface Timezone Conversion

### Simple Command Line program that finds the current time anywhere in the world using timezone conversion

## How to use:

The format takes three arguments & which is as follows: "node <script-file> <timezone>". Node & <script-file> (index.js) are already declared, and the default timezone is for Chicago, Central Standard Time.

Type "npx cml-timezone-conversion" to run locally

In Terminal, type "node index.js "America/Los_Angeles" or whichever location to see the current time & timezone of that location. The same 3 argument format (node || index.js || <timezone>) will work with any major city & timezone.

Once the app is run, the data will be displayed as such:

"The time at the America/Los_Angeles timezone is 2022-09-25T22:04:43-07:00"

> See Moment Timezone[https://momentjs.com/timezone/] npm docs for further detais regarding avaliable timezones
