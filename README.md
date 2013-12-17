Google Authenticator Database-to-QR converter
=============================================

So, you've got a new Android phone and you want to move over
(or perhaps copy) your Google Authenticator (which might include
<a href="http://itservices.stanford.edu/service/webauth/twostep"/>more</a>
<a href="http://drupal.org/project/ga_login"/>than</a>
<a href="http://www.mnxsolutions.com/security/two-factor-ssh-with-google-authenticator.html">one</a>
<a href="http://helpdesk.lastpass.com/security-options/google-authenticator/">account</a>).
This workflow only works when the source device is <em>rooted</em>.
Otherwise, the only way to get the Google Authenticator database out
of the device is to root it.

You will need
-------------
1. Your old **rooted** Android device.
2. Your new Android device -- doesn't have to be rooted.

Instructions
------------
1. Download the repository as a ZIP file.
2. Extract the ZIP and open the index.html file in your browser (Google Chrome works). Do it locally. This script doesn't need any network access.
3. Follow the directions.

Background
----------
I've made this tool mostly to see how quickly I could whip one up with a bunch of existing code (sqlite.js and a QR code generator). It's pretty cool how nowadays one can make a local app like this. Yep, no server-side here at all.
