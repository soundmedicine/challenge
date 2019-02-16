# challenge
mParticle sample mobile app in Xcode and Swift

## event tracking

### event builder object for custom events (Swift)

`let event = MPEvent(name: "Video Watched", type: MPEventType.navigation)

event?.info = ["category": "Destination Intro", "title": "Paris"]; 

if (event != nil) {
    MParticle.sharedInstance().logEvent(event!)
}`

