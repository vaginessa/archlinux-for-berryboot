# Converting ArchLinux ARM OS for Berryboot
This is a simple bash script to download and convert ArchLinux OS image for Berryboot.
<h2>Usage</h2>
First, allow to execute the script by change the permission:
<pre>chmod +x archlinux_berryboot.sh</pre>
Then, simply run the script as root and select your device.
<pre>sudo ./archlinux_berryboot.sh</pre>
This script will:
<ul>
 	<li>Download the latest ArchLinux OS image</li>
 	<li>Decompress downloaded image</li> 	
 	<li>Generate squashfs Berryboot image file</li>
</ul>
NOTE: This script will need squashfs-tools and bsdtar, make sure your OS have those packages installed before execute the script.<a target="_blank" href="http://www.alexgoldcheidt.com/wp-content/uploads/sites/5/2017/03/archlinux-berryboot-demo.png"> Quick Screenshot</a>

For already converted OS images, go to: <a target="_blank" href="http://berryboot.alexgoldcheidt.com/images/">http://berryboot.alexgoldcheidt.com/images/</a>

&nbsp;
