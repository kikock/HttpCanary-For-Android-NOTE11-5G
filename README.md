# Http-Canary-For-Android-11Backup-file
This is just a backup repo for me to install http Canary in Android 11 , i don't need to search the internet for this modded application


Make sure your device is rooted before following this guide.

# Installation

Firstly, install HttpCanary as you normally would from the website here.

After it is installed, go through the usual setup ignoring the fact you cannot install the certificate.

After the setup, completely close the app.

# Method 1 : 

## Manual Fix for  installing the certificates

### Device Must and Rooted

1. Install http Canary app

2. INSTALL Mt Manager app or any root file explorer 

3. Using ES File Explorer (I had problems using other root browsers), head over to `/data/data/com.guoshi.httpcanary.premium/cache` and copy `HttpCanary.pem` and `HttpCanary.p12` to your phones accessible storage (such as Downloads or Documents).

4. Open up the 'settings app > Biometrics & Security > Other Security Settings > Install from device storage'.

5. Select CA certificate and press 'install anyway'.

6. Browse to 'HttpCanary.pem' and install it.

7. On the 'Install from device storage' screen, now press 'VPN and app user certificate'

8. Browse to 'HttpCanary.p12' and enter the password which is 'HttpCanary' and do not modify the name.

9. Fixing the application to detect the certificates

10. Head back over to `/data/data/com.guoshi.httpcanary.premium/cache` and create an empty file named `HttpCanary.jks`.

11. Create a copy of the 'HttpCanary.pem' file in the same directory and rename it to `87bc3517.0`.

12. That's it 
