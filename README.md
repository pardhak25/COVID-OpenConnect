# COVID-OpenConnect
Track of Open connection around you using bluetooth.

## Background
In view of COVID-19 out-break, thought to have an app that keep track of the unique mobile devices that are in the near field of less than 10mts.

### How it helps to track the chain
For example you are a charity member / a citizen providing support for the needy; you many connect to people and you don't know how their health is going to be after 10days. By installing this app on all mobiles it keeps track of unique-mobile ids that are surrounded by you in less than 10mts. 

The App automatically scans frequently and captures the surrounding mobile ids. The captured information is stored in mobile and synced to central database; data is stored for a period of 21days.

If member(A) of this app is tested with COVID +ve; he / his close member submit his status in the app; it will trigger the notification to all other community members with whom (B) he have connected in past 20days. Those who got the notification has to be self quarantine for few days to be safe for your family and rest of the community. If member (B) also +ve then it will send notification to his connected devices. 

***We only track the MAC address of the two open connect mobiles and stored in our database.***

***This is to track Open-connected people (Social connected) and not for Close connected like your family members staying in a single home***

## Blue Print
- Community member has to install the app on their mobile and grant permission for app to control Bluetooth.
- App register to server with unique id and some additional details
  - Android / IOs Device ID
  - IMEI (optional)
  - SIM SubscriberID
  - WI-FI MAC Address
  - Bluetooh DeviceID
- Member who staying at one home has to set other devices in their family to group and those will be filtered from the tracking.
- Member has to update home location(optional), so app can automatically on its track when you away from your home.
- App will scan near by devices and stores the information that you are open connected in a day.
- Any community user who tested +ve has to inform in the app and all the open connected devices in last 20days will be get notified. This app is not sharing your personal information and it just alerts with your unique registered ID.
- All the users have to self quarantine for few more days and any symptoms they have to reach Govt Authorities.
- Additional steps to keep every citizen safe and secure.  
  - Members health information tracking.
  - Quarantine days tracking.
  - Sharing health tips during the quarantine period.

## Contribution
Invite everyone to contribute your support and ideas to improve this app more helpful to everyone.

## License
COVID-OpenConnect is released under the MIT License.
