# How to build a website that will (eventually) work on Mars

## Abstract

At not so distant future human race will be able to make a colony on Mars, and we’ll need a stable communication between the planets. Interplanetary internet works differently (ie. 3.5 to 22 mins delay between planets), so what from today’s technologies can we use to build an interplanetary web app?

## More info

At not so distant future human race will be able to make a colony on Mars, and we’ll need a stable communication between the planets.

Interplanetary internet works a bit different than we would expects (ie. there’s a delay of minimum 3.5 to 22 minutes between the planets) and it also brings new protocols etc.

Idea of this talk is to try to put technologies available in the browser today together and to make a website (actually a web app) that would eventually work on Mars even before we have full infrastructure there too.

An example? Ok, so, since there’s a huge delay between the planets (minimum 3.5-22 minutes) TCP/IP doesn’t work anymore, there’s some new protocols (DTN, etc.) Imaging a news website that people from Mars use to see the news from Earth. First we don’t want to ping the servers on Earth all the time, we need to use Service Workers for full offline cache and strong background sync and IndexedDB for a local storage. Even with that, no one want’s to wait for a new updates for 7-44 minutes, so we should probably use WebRTC to load news and other new resources peer-to-peer between people on Mars and to have some background sync with Earth servers. What about media? Well, we can use WebRTC too, there’s Web torrent and some other technologies that can help with peer-to-peer loading and streaming video and other media files. And there’s many more things we can use.

This is obviously just a talk for fun, things will evolve much more until the moment we start building a colony on Mars.

## Where and when

### Full Stack Fest 2016, Barcelona

#### Location and date

Full Stack Fest 2016, Barcelona on September 9, 2016.

#### Slides

[![Slides from Full Stack Fest 2016, Barcelona](https://speakerd.s3.amazonaws.com/presentations/55b6bc0cb30440b3b68b3cc52f578760/slide_0.jpg)](https://speakerdeck.com/slobodan/how-to-build-a-website-that-will-eventually-work-on-mars)

#### Video

[![Video from Full Stack Fest 2016, Barcelona](http://img.youtube.com/vi/7rlEidtXlZg/0.jpg)](https://youtu.be/7rlEidtXlZg)

### Web Camp 2016, Zagreb

#### Location and date

Web Camp 2016, Zagreb on October 28, 2016.

#### Slides

[![Slides from Web Camp 2016, Zagreb](https://speakerd.s3.amazonaws.com/presentations/b9ab52a22ef44dbc867971918c5b888d/slide_0.jpg)](https://speakerdeck.com/slobodan/how-to-build-a-website-that-will-eventually-work-on-mars-v1-dot-1-0-webcamp-zagreb-2016)

#### Video

[![Video from Web Camp 2016, Zagreb](http://img.youtube.com/vi/9xxmV4q6JEQ/0.jpg)](https://youtu.be/9xxmV4q6JEQ)

## Other links

- [Papercall.io page](https://www.papercall.io/speakers/slobodan/speaker_talks/3663-how-to-build-a-website-that-will-eventually-work-on-mars)
- [JoindIn feedback from Zagreb](https://joind.in/event/webcamp-zagreb-2016/how-to-build-a-website-that-will-eventually-work-on-mars)