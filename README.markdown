## Welcome to the home of Scribe, the simple OAuth Java lib!

## Why use Scribe?

## Dead Simple

`@OAuthService service = new ServiceBuilder()
                                  .provider(LinkedInApi.class)
                                  .apiKey(YOUR_API_KEY)
                                  .apiSecret(YOUR_API_SECRET)
                                  .build();`
                                  
That **single line** (added newlines for readability) is the only thing you need to configure scribe with LinkedIn's OAuth API for example.

## Threadsafe

Hit Scribe as hard and with many threads as you like.

## Supports all major 1.0a and 2.0 OAuth APIs out-of-the-box

* Google

* Facebook

* Yahoo

* LinkedIn

* Twitter

* Foursquare

* Evernote

* Vimeo

* Yammer

* Windows Live

* and many more! check the "examples folder":http://github.com/fernandezpablo85/scribe-java/tree/master/src/test/java/org/scribe/examples

## Small and modular

Scribe's code is small (about 1k LOC) and simple to understand. No smart-ass or "clever" hacks here.

## Android-Ready

Works out of the box with android(TM) applications.

## Stable & bulletproof

Good test coverage to keep you safe from harm. 

When something bad actually happens, Scribe's meaningful error messages will tell you exactly what went wrong, when and where.

## Pull it from Maven! (new)

You can pull scribe from a maven repository, just add this to your __pom.xml__ file:

`<dependency>
  <groupId>org.scribe</groupId>
  <artifactId>scribe</artifactId>
  <version>1.2.3</version>
</dependency> `

## Getting started in less than 2 minutes

Check the "Getting Started":http://wiki.github.com/fernandezpablo85/scribe-java/getting-started page and start rocking!

## Please Read the "FAQ":http://wiki.github.com/fernandezpablo85/scribe-java/faq before creating an issue :)

