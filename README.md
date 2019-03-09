# Android Architecture Components (Maybe) - Sample
No I dont recommend any framework that makes you worship proprietary code rather open source. I prefer greater code control and loosely coupled code designed carefully in terms of abstraction. What I saw in LiveData was too much code and making your classes too much dependent on application framework than business layer. So its good for some cases, but not all. In fact one good advantage is that they come in separate packages so we can choose whichever suits our needs, and the best package for me was Room library for Spring-like ORM. 


In general, AAC is targetted for bringing MVVM architecture forward and standardize it in Android Development, but these AAC components can be used separately in other architectures like MVP, or VIPER. And with currently available Rx Extensions, we can make our project-suited version of architecture ourself that is fast, robust, maintainable and testable all at the same time.

This sample aims at similar approach of using some AAC things, Kotlin and other popular libraries including Rx to test the idea of choosing a flexible architectural design, rather than worshipping a proprietary or open source framework blindly. For this, a good understanding of layering the application details into slices and abstraction of components from each other is necessary. Simply SOLID principles at your disposal is what you need to challenge, question and follow anything regarding architectural design when starting a new project, that not just please the managers or developers, but helps writing a reliable code that is generating some good business value.

## MVVM Sample using Kotlin, Rx, Dagger, Butterknife, Retrofit, Room and StackOverflow!
