 ![ScreenShot](https://github.com/optio50/PIA-Server-Check/blob/master/PIA.png?raw=true|alt=octocat)
  ![ScreenShot](https://github.com/optio50/PIA-Server-Check/blob/master/PIA2.png?raw=true|alt=octocat)
   ![ScreenShot](https://github.com/optio50/PIA-Server-Check/blob/master/PIA3.png?raw=true|alt=octocat)
    ![ScreenShot](https://github.com/optio50/PIA-Server-Check/blob/master/PIA4.png?raw=true|alt=octocat)
    ![ScreenShot](https://github.com/optio50/PIA-Server-Check/blob/master/PIA5.png?raw=true|alt=octocat)
# PIA-Server-Check
Find the Fastest PIA (Private Internet Access) VPN server in Your Country (Auto or Manual)

Geo Location Readout

PIA Protection Check

Download Speed Test with Auto Select Fastest Server

DNS Leak Test (Hackish / Experimental)

Show PIA Server Names

Check to make sure you are not connected to a "Virtual VPN Server" instead of real hardware in the selected city.

This script can do others thing not strictly related to PIA that non-subscribers can use.
Change your MAC address   
Speed Test your connection    
DNS Leak Test    
Show your Geo-Location-IP information and verify the VPN location is REAL by using ping.pe website.

==========================================================================

Netselect is required.

Netselect needs to run as an administrator user (i.e. root). This is only required because the network probes done by netselect requires these permissions. No changes are done to the system.
You can download it from

http://ftp.us.debian.org/debian/pool/main/n/netselect/

http://ftp.us.debian.org/debian/pool/main/n/netselect/netselect_0.3.ds1-28+b1_i386.deb		i386

http://ftp.us.debian.org/debian/pool/main/n/netselect/netselect_0.3.ds1-28+b1_arm64.deb		ARM64

http://ftp.us.debian.org/debian/pool/main/n/netselect/netselect_0.3.ds1-28+b1_armhf.deb		ARMHF

http://ftp.us.debian.org/debian/pool/main/n/netselect/netselect_0.3.ds1-28+b1_amd64.deb		AMD64


install with sudo dpkg -i netselect_0.3.ds1-28+b1_*.deb

Script will offer to download and install netselect curl and or wget if you dont have them installed. Ubuntu or similar distro only (apt & sudo)


This PIA script will offer some default countries for selection or check ALL the server PIA offers.

 
Select Country

0. ALL SERVERS PIA OFFERS
1. U.S.
2. UK
3. Canada
4. Australia
5. New Zealand
6. Germany
7. Hong Kong
8. Japan
9. Israel
 
Checking For PIA's Fastest server...Please Wait.

Fastest Server

us-siliconvalley.privateinternetaccess.com

us-siliconvalley.privateinternetaccess.com Has 13 IP Address's

Checking For The Fastest IP Address To us-siliconvalley.privateinternetaccess.com 

199.116.118.251 25.976ms

Main Script File Is PIA

To use this script make the file executable by typing
chmod +x PIA

Then run it from the downloaded directory by typing
./PIA



