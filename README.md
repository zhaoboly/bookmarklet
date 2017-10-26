# QR Bookmarklet for Mobile phone

## Why we need it
* Starting from 2017, iPhone's camera app can read QR codes. Check [this link](http://www.iphonehacks.com/2017/09/how-to-scan-qr-codes-iphone-ipad-ios-11.html) for more details.

## Add this bookarklet to the browser

Drag this link onto the browser's bookmark bars.

<a class="" href="javascript:void((function()%7bvar%20sl;if(window.getSelection)%7bsl=%22%22+window.getSelection();%7delse%20if(document.selection)%7bsl=document.selection.createRange().text;%7ddata=encodeURIComponent(sl%7c%7clocation.href);var%20win=window.open(%22http://www.scan2d.com/tools/share.htm?url=%22+data,%22_blank%22,%22width=550,height=625,resizable=yes,status=yes,replace=true%22);win.focus();setTimeout(function%20(){win.close();},20000);%7d)())">Open in Mobile</a>


When you click the button, it will generate a QR code of the page you are visiting.


## Features
* You can highlight any text on the page and hit the button. A QR code based on that text will be generated.


