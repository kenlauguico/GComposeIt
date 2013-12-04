gComposeIt
==========
I sadly was looking for the old Feedly Mini toolbar that came pre-installed with the Feedly extension (before the entire Google Reader drop-out era) and I really fell in love with that little toolbar!

I mainly used it to share content, specifically to email the current page (on any current page) to a friend without any mess or hassle.

## Usage

Simply stick the following Javascript code into your bookmarks bar.

     javascript:var t=encodeURI(document.title);var u=encodeURI(window.location);window.open('https://mail.google.com/mail/?view=cm&fs=1&tf=1&su='+t+'&body='+u);
     
That's it!