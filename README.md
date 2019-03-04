# urlShortener

##UrlShortener is an application that shortens urls and also redirects already sortened urls to original ones. 

It was developed using **Spring Data Redis**

To run this project you need to:

1. Download Redis 

2. Make sure Redis is running

3. Run ```mvn install``` standing in Project folder, this will generate a jar of the project inside Target folder

4. Run ```java -jar pathToJar``` on command line

5. You can use postman and do a post to localhost:8080?urlToShorten

6. Then you can insert the shortend url in the browser and it will be redirected to the original url
