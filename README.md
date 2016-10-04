# Network Device Pinger
A simple python script to test the connectivity/availability of a network device

!!!!! As of the time of this README (midnight, 10/4/2016), it is able to detect when a device is online, but it is 
not (always) able to detect when the device is offline. It has something to do with whether the command line 
returns that the packets timed out, or whether it says it didn't receive a reply. !!!!!

This python script allows a user to log in with their email account (tested with @gmail.com, and currently is hard
coded with the gmail smtp server), and ping a network device.
If the device is offline at any point, the script should use the email address to send a formatted text message
to the designated phone number.

- Michael Crinite
- 10/4/2016
