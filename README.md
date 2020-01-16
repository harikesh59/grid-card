# STOCKS 

# What does this app do?
It is an  Android application that allows user to watch stocks update in real time. User can watch 
last traded price, High, Low, Day change etc. of a stock.

# Libraries this app uses:

1. RxKotlin - https://github.com/ReactiveX/RxKotlin
2. Retrofit - https://github.com/square/retrofit
3. Dagger - https://github.com/google/dagger
4. OkHttp - https://github.com/square/okhttp/
5. Glide Image Loading - https://github.com/bumptech/glide
6. MPAndroidChart - https://github.com/PhilJay/MPAndroidChart

## Sample app
Download sample app from this link - 


## Clean Architecture
This project follows clean Architecture. The overriding rule that makes this architecture work is 
The Dependency Rule. This rule says that source code dependencies can only point inwards. Nothing 
in an inner circle can know anything at all about something in an outer circle. In particular, 
the name of something declared in an outer circle must not be mentioned by the code in the an inner
circle. That includes, functions, classes. variables, or any other named software entity.

Sqlite Database is used for caching stock prices in this
project.
![](https://blog.cleancoder.com/uncle-bob/images/2012-08-13-the-clean-architecture/CleanArchitecture.jpg)
