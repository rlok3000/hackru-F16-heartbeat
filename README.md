# hackru-F16-heartbeat

# Inspiration
Patients aren't always limited to the hospitals. Pulse is an app designed as a life alarm system to prevent and forewarn its user of the dangers of exceeding normal heart rate thresholds while awake and especially in their sleep. 

# What it does
Pulse tracks its user's heart rate with the portable monitor and sends a call depending on the severity of the heart rate fluctuation. Upon successful registration, the user is sent a call once the heart rate reaches "warning" level. When the "danger" level is reached, a call is made to the user; if the call is unsuccessful, the registered emergency contact is sent a call.

# How we built it
MongoDB implementation on a Linux server using Linode, telecommunication via Twilio, and data tracking using a Polar H7 low energy bluetooth heart monitor comprise the entirety of this project.

# Challenges we ran into
Setting up enviroment within Linode remote box to run node app. 

# Accomplishments that we're proud of
Telecommunication system implementation that emphasizes the safety of the user.

# What we learned
Data tracking accuracy is often directly proportionate to equipment cost. Accompanying heart rate monitor software to cheaper products may also account for numerical results. Individuality in constitution and health require tweaking of heart rate thresholds to accommodate these differences.

# What's next for Heartbeat
More accurate software and hardware to diagnose heart rate using algorithmic predictions. Possible app sharability with Pebble and vocal commands.

# Built With
mongoDB
linode
node.js
Xcode
Swift
Twilio
Github
