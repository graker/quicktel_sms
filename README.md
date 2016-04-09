# Quick Telecom SMS

Drupal 7 module for Quick Telecom SMS gateway integration. This module doesn't integrate with SMS Framework, at least for now. 
It's a stand alone module to send SMS using Quick Telecom gateway (http://www.qtelecom.ru/).

Supported features:
 - config page with login, password and remaining balance
 - HTTP/HTTPS protocol implementation
 - Sender field support (you have to register sender in the service prior to use)
 - Time period support (limit SMS sending to certain time of the day)
 - Send SMS to one or multiple recipients using quicktel_sms_send() function.
 
### To install:
 - download and enable the module as usual
 - go to admin/config/services/quicktel-sms and configure the module
 - send messages using quicktel_sms_send($phones, $message) function where $phones is an array of valid mobile numbers and $message is a text to send.

 