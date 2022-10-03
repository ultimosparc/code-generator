# code-generator
Inspired by the project SecScanQR (https://github.com/Fr4gorSoftware/SecScanQR), I created an REST-API for creating bar and qr codes. How to create an API, check out the online article on baeldung.com (https://www.baeldung.com/java-generating-barcodes-qr-codes) for more details.
## Technical details
- I host my app on the cloud application platform heroku (https://www.heroku.com), since their services are free for open source projects and it's a such easy way to deploy apps on this platform.
- I host the API on the server https://universal-code-generator.herokuapp.com.
- Currently, I use the Barbecue library to create linear bar codes and the QRGen library to create qr codes.
- The following bar codes are supported: EAN13, PDF417, Code128
- Default image resolution is 160
## Samples
![image](https://user-images.githubusercontent.com/15387251/193482581-c106e2f0-7917-46f3-801e-4a2710992c94.png)
![image](https://user-images.githubusercontent.com/15387251/193482602-774adb57-5487-48a2-91b4-97c7621cf06b.png)
![image](https://user-images.githubusercontent.com/15387251/193482652-3bc90506-1ec1-4028-a4ef-f092dd23cb59.png)
![image](https://user-images.githubusercontent.com/15387251/193482762-5bb5b313-fa28-4c44-9f87-462d21c86a00.png)





