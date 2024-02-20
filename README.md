# V-Fingerprint
This repo contains files for interfacing fingerprint sensors BFM808 and Waveshare optical fingerprint module.

DualFingerDemo.ino
Coded for 2 waveshare fingerprint sensors connected to uart1 and uart2 in a arduino mega.
Code demonstrates how to enroll a finger from one sensor and transfer the vector data to other sensor with same user id, so the user is identified
in both sensors for same user id.

capacitiveFP.ino
Used to interface a BFM808 fingerprint sensor. Its english datasheet has many missing data which makes interfacing tha sensor difficult. Seller shared missing data from a chineese sourse but require transtation. CRC check function is verified and sensor replies for commands. 
