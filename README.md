# Issue

I upgraded to MacOS 14.1.1 and since then I can't use MapStruct anymore. I get an IllegalAccessError. It was working 
before the OS update and to verify and try different combinations of Java, Kotlin, ... mapstruct versions I created this
small project.

Whatever I did on my 14.1.1 machine I couldn't build it except by doing the build within a docker container - based on 
the same code.

Tried with:
 - Java 17 (tem + graal)
 - Java 21 (tem + graal)
 - Kotlin 1.8
 - Kotlin 1.9
 - MapStruct 1.6.0.Beta1
 - MapStruct 1.5.5.Final
