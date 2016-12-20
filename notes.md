#Best practices

###Good Client-specific boilerplate styles to add to header  
Note: OK to add to header because none are Gmail-specific (Gmail will(did?) strip styles from the header)

```html
/* CLIENT-SPECIFIC STYLES ---------------------------------------- */
#outlook a {
  padding: 0; /* Force Outlook to provide a "view in browser" message
}

.ReadMsgBody {
  width: 100%; /* Force Hotmail to display emails at full width */
}

.ExternalClass {
  width: 100%; /* Force Hotmail to display emails at full width */
}

.ExternalClass,
.ExternalClass p,
.ExternalClass span, 
.ExternalClass font,
.ExternalClass td,
.ExternalClass div {
  line-height: 100%; /* Force Hotmail to display normal line spacing */
}

body, table, td, a { /* Prevent Webkit and Windows mobile from changing default text sizes */
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
}

table, td { /* Remove spacing between tables in Outlook 2007 and up */
  mso-table-lspace: 0pt;
  mso-table-rspace: 0pt;
}

img { /* Allow smoother rendering of resized image in IE */
  -ms-interpolation-mode: bicubic;
}

```

###Good reset boilerplate to add to header
```html
body {
  height: 100% !important;
  width: 100% !important;
  margin: 0;
  padding: 0;
}

img {
  border: 0;
  height: auto;
  line-height: 100%;
  outline: none;
  text-decoration: none;
}

table {
  border-collapse: collapse !important;
}
```

#####Mon Dec  5 09:10:49 2016 CST
* [dragula - Browser drag-and-drop so simple it hurts](https://bevacqua.github.io/dragula/)

#####Wed Dec  7 09:37:08 2016 CST
* Do we want to add Tweet This? buttons to articles?

#####Thu Dec  8 10:30:30 2016 CST
* [Jason Rodriguez on CodePen](http://codepen.io/rodriguezcommaj/pens/public/)
    * Jason gave the Front-End Masters presentation on Responsive HTML Email Design
    * These are the example he presented

* [The Ultimate Guide to Styled ALT Text in Email](https://litmus.com/blog/the-ultimate-guide-to-styled-alt-text-in-email)

* [CSS Support Guide for Email Clients | Campaign Monitor](https://www.campaignmonitor.com/css/)

* [Bulletproof email buttons | Campaign Monitor](https://buttons.cm/)

* [Which clients support media queries? - Help – Litmus](https://litmus.com/help/email-clients/media-query-support/)

* [How To Ban Blue Links on iOS Devices In Email](https://litmus.com/blog/update-banning-blue-links-on-ios-devices)

* [Email Client Market Share and Popularity - November 2016](https://emailclientmarketshare.com/)

* [Our Favorite Responsive and Mobile Email Resources – Litmus Software, Inc.](https://litmus.com/blog/our-favorite-responsive-and-mobile-email-resources)

* [Discussions](https://litmus.com/community/discussions)

* [The Best Email Marketing Campaigns of 2016 | Campaign Monitor](https://www.campaignmonitor.com/best-email-marketing-campaigns/)

* [Responsive Email Patterns](http://responsiveemailpatterns.com/)

* [Responsive Email Resources](http://responsiveemailresources.com/)

* [rodriguezcommaj/salted: A responsive email template](https://github.com/rodriguezcommaj/salted)

* [Litmus Scope](https://litmus.com/scope/)
    * Like a "View Source" for email

#####Tue Dec 20 11:12:26 2016 CST
* [localfont.com - Download fonts from googlefonts](http://www.localfont.com/)
