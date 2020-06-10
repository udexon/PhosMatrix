# PhosMatrix
PhosMatrix

From World Wide Web to Man Machine Matrix: Transforming the Web with Transient Key Cryptography and Metashellet

:: Emphasize both TKC and Metashellet

If we are asked to name one technology that completely change the way we deal with information, that would be the World Wide Web.

Yet, the web is built with one of the oldest and perhaps outdated technology from the Unix era, the user ID authentication system.

With the popularity of Cryptocurrencies, transient key cryptography is now gaining more attention as an alternative to the asymmetric cryptography underlying the Unix User ID authentication system.

With TKC, we can build a new Man Machine Matrix, MMM, as a pun to the outdated World Wide Web.

However, as we shall demonstrate later in this article, MMM is more than just a pun to WWW, with significant and practical breakthroughs. 

Conventional app restricts user interactions to features and services predefined by code. MMM liberates that. Every user is now a programmer, much like the human in Matrix the film series. 

We call our implementation of MMM PhosMatrix.

To illustrate the practical significance of MMM or PhosMatrix, consider a DJ who wish to mix two or more audio sources from the Internet and stream it live to his (her) listeners online.

With the conventional Unix style user ID authentication system, someone would have to build a new website with full audio mixing and streaming capabilities, together with a full fledged user ID authentication system. Website functionalities such as the user ID authentication system is actually the low cost part of the business. The expensive part is actually the time and effort required to build up the user base.

Suppose the DJ gets rid of the user ID authentication system, so that he can serve his music to any listeners. By doing this, he loses the possibility of tracking his listeners and make money from his listeners in the future. 

He may adopt an "opt in" arrangement, where he allows everyone to listen to his music, but users need to sign up to enjoy more benefits. Again, building up the user base is expensive and time consuming. 

- How would transient key cryptography change the situations?

In the conventional software development models, the server and client for the application above are vertically integrated to include all functionalities, from UI, user ID authentication, mixing, delivery and playback. 

TKC allows the server and client software to be broken up, liberated from the UI and user ID authentication, thus making the UI a thin wrapper to interface with low level, tried and tested, bread and butter tools and libraries such as ffmpeg.

Yes. You hear it right. 

PhosMatrix will allow the good old ffmpeg to be used as the back end of a live streaming software, with a thin layer of UI. 

Using the old web and Unix User ID authentication conventions, a web server interacts with a user via a client (mobile app or browser).

With TKC, a user may execute a script, sending commands to a server, and receive the results as a json string or binary file.

The crucial difference between a PhosMatrix app vs. a conventional web app arises from the need of a user to login when using a conventional web app. Since the conventional web app is vertically integrated, the functionalities are designed and restricted based on the user's role.

In PhosMatrix however, since authentication is achieved using TKC, a client can interact with a server in a much more unrestricted manner, making its design more flexible.

To be more specific, consider the following scenarios:

A) Audio mixing and streaming app with Conventional Unix User ID authentication

B) Audio mixing and streaming app with transient key cryptography  authentication

C) Audio mixing and streaming app without any of the User authentication above

To implement scheme C, we may use the following components:

1. Use ffmpeg live stream features:

http://trac.ffmpeg.org/wiki/EncodingForStreamingSites

2. Mix multiple audio sources with ffmpeg:

https://stackoverflow.com/questions/14498539/how-to-overlay-downmix-two-audio-files-using-ffmpeg

3. Broadcast the output file via http server.

In designing and implementing scheme A, scheme C is usually used as a prototype and reference. Subsequently, the client and server module will be vertically integrated to include all functionalities from user authentication, mixing, playback to UI.

This has become the mainstream practice that no one seems to question. 

By comparing the development effort required for scheme C and scheme A, is it possible that scheme B can achieve the best of both worlds?


# GUI Factors: Solutions from Metashellet

Scheme A is GUI oriented.

Scheme C is CLI.

Conventional GUI has no programming interface -- Phoshell reconciles both.






How to share file?

User ID is a temporary nickname derived from chain of public keys.

UID maps to devices accessible by User @uid 

Then path, or database, URI.

User download video files, edit and mix audio, output to video files. Share files as service or stream video out

Just let user use plain http to send message, retrieve files to and fro?

Interface is another layer?

