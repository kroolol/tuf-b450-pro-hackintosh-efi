# TUF B450 PRO - GTX 1060 Hackintosh EFI


Specs:


CPU: AMD Ryzen 3 3100 


Motherboard: ASUS TUF GAMING B450 PRO (BIOS Ver. 4202)


Memory: 8 GB DDR4 3200 MHz


GPU: ASUS Dual GeForce GTX 1060 6 GB


System Disk: KIOXIA EXCERIA NVMe SSD 250 GB




<img src="https://techolay.net/sosyal/ek/1703854415044-png.4823/">





<article>
  <header>
    <h1>Tested Versions</h1>




<!DOCTYPE html>
<html>
<head>
 
</head>
<body>
 
<table border=1>
    <tr>
        <td>Big Sur 11.7.1</td>
    </tr>
    <tr>
        <td>Monterey 12.6.6</td>
    </tr>
    <tr>
        <td>Ventura 13.4</td>
    </tr>

   
</table>

</body>
</html>









<article>
  <header>
    <h1>Features</h1>





Ryzen Power Management (You also need to install the AMD Power Gadget app.)


GPU Acceleration (OCLP root patch is required. Other than that, with the other necessary boot args implemented in EFI, there's nothing extra you need to do.)


Ethernet


Apple Services (Serial number may need to be regenerted.)


Audio (Depending on the audio equipment (headphones an etc.) you are using "layout id" value may need to be changed.)


<article>
   <header>
     <h1>Possible Issues</h1>






<table border="1">
    <body>
        <tr>
            <td>&nbsp;</td>
            <td>Causes</td>
            <td>Solution<br />
            </td>
        </tr>
        <tr>
            <td>The black screen in Photos and Maps app on Monterey. (and Apple Maps-based windows in other apps)</td>
            <td>These applications work based on the Metal API on Monterey</td>
            <td>Downgrade to Big Sur</td>
        </tr>
        <tr>
            <td>Frame drops on Discord.</td>
            <td>Probably due to non-Metal API.</td> 
            <td>Disable ''Hardware Acceleration'' in Discord.</td>
        </tr>
    </body>
</table> 




