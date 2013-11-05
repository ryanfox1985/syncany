ABOUT SYNCANY
-------------
Syncany is an open-source file synchronization and filesharing application. It
allows users to backup and share certain folders of their workstations using any
kind of storage, e.g. FTP, Amazon S3 or Google Storage.

While the basic idea is similar to Dropbox and JungleDisk, Syncany is
open-source and additionally provides data encryption and more flexibility in 
erms of storage type and provider:

- Data encryption: Syncany encrypts the files locally, so that any online
  storage can be used even for sensitive data.

- Arbitrary storage: Syncany uses a plug-in based storage system. It can be 
  used with any type of remote storage.
  
Find more information and an up-to-date list of the currently supported storage
types on http://www.syncany.org/


INSTALLATION & REQUIREMENTS
---------------------------
To install Syncany on your computer, check out the INSTALL document
for detailed instructions. If you are a developer, please read the
DEVELOPMENT file instead.


AUTHORS
-------
Idea & Development
   Philipp C. Heckel <philipp.heckel@gmail.com>
   Guillermo Guerrero <gguerrero1985@gmail.com>
   

DONATE
-------
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_donations">
<input type="hidden" name="business" value="gguerrero1985@gmail.com">
<input type="hidden" name="lc" value="US">
<input type="hidden" name="item_name" value="Syncany">
<input type="hidden" name="no_note" value="0">
<input type="hidden" name="currency_code" value="EUR">
<input type="hidden" name="bn" value="PP-DonationsBF:btn_donateCC_LG.gif:NonHostedGuest">
<input type="image" src="https://www.paypalobjects.com/es_XC/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal, la forma más segura y rápida de pagar en línea.">
<img alt="" border="0" src="https://www.paypalobjects.com/es_XC/i/scr/pixel.gif" width="1" height="1">
</form>

LICENSE
-------
The software components of Syncany, as well as its images and plugins are
distributed under different compatible open source licenses:

- Syncany is distributed under the GNU General Public License Version 3.
  Refer to the LICENSE document for details.

- The Syncany extension for Nautilus is based on the Dropbox Nautilus extension
  (https://www.dropbox.com/downloading?os=lnx). It is distributed under the
  under the GNU General Public License Version 3.

- The emblems for the Nautilus extension are based on the 'mail-mark-notjunk'
  and 'battery_emtpy' icons of the Faenza Icon Theme
  (http://gnome-look.org/content/show.php/Faenza?content=128143), which is
  distributed under the GNU General Public License Version 3.
  
- The Syncany WebDAV plugin uses the Sardine Java library 
  (http://code.google.com/p/sardine/). It is distributed under the 
  GPL-compatible Apache License 2.0.
  
- The Syncany Rackspace plugin uses the java-cloudfiles library provided by
  Rackspace (https://github.com/rackspace/java-cloudfiles). It is distributed
  under the GPL-compatible MIT License.

