# demo-spring-HelloName
Simple Spring Framework application using Spring Boot

The hello() method is designed to take a String parameter called *name*, and then combine this parameter with the word *"Hello"* in the code. This means that if you set 
your name to “Tomiris” in the request, the response would be “Hello Tomiris!”. Default *name* parameter is set to *"World"*.

You can run the application by using mvnw _**spring-boot:run**_ command on Windows and _**./mvnw spring-boot:run**_ on MacOS/Linux. 

You can find default response on _localhost8080/hello?name_, and also set your own *name* parameter.
