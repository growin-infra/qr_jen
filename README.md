# A simple Spring Boot application generating QR Codes.

Features
--------

A simple [Spring Boot](http://projects.spring.io/spring-boot/) standalone application generating QR Codes based on
[ZXing ("Zebra Crossing")](https://github.com/zxing/zxing/) barcode scanning library.

Build & run 
-----------

**Prerequisites:**

* Java 18
* Apache Maven (https://maven.apache.org/)
* External tomcat 8.0

Application properties can be configured in

```bash
/qr_jen/src/main/resources/application.properties
```

Use

```bash
Run as > Maven Clean
```
to build the application and

```bash
Run as > Maven Bulid
```

to run it on your development machine.

```bash
Tomcat 8.0
```

Point your browser to 

```bash
http://localhost:8180
```


