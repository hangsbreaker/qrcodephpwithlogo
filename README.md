# qrcodephpwithlogo
Create QR Code with PHP and logo in the QR Code

PHP QR Code is open source (LGPL) library for generating QR Code, 2-dimensional barcode. This is the web page.
http://phpqrcode.sourceforge.net/
The web page tell Some of library features includes:
<ul>
<li>Supports QR Code versions (size) 1-40</li>
<li>Numeric, Alphanumeric, 8-bit and Kanji encoding. <span style="color: silver; font-size: 0.8em;">(Kanji encoding was not fully tested, if you are japan-encoding enabled you can contribute by verifing it :) )</span></li>
<li>Implemented purely in PHP, no external dependencies except GD2</li>
<li>Exports to PNG, JPEG images, also exports as bit-table</li>
<li>TCPDF 2-D barcode API integration</li>
<li>Easy to configure</li>
<li>Data cache for calculation speed-up</li>
<li>Provided merge tool helps deploy library as a one big dependency-less file, simple to "include and do not wory"</li>
<li>Debug data dump, error logging, time benchmarking</li>
<li><a href="http://phpqrcode.sourceforge.net/docs/html/index.html" title="API Documentation">API documentation</a></li>
<li><a href="http://phpqrcode.sourceforge.net/examples/index.php" title="Usage examples">Detailed examples</a></li>
<li>100% Open Source, LGPL Licensed</li>
</ul>
To minimal using just include qrlib.php
then write code
QRcode::png('some othertext 1234'); //creates code image and outputs it directly into browser
