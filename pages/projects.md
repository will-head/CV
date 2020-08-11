<< Back to [will-head/CV](https://github.com/will-head/CV)

## Projects

### Chronomy

The goal of the project is to provide a curated playlist of [TikTok](https://www.tiktok.com/) videos.

Created as part of [Makers Academy's](https://makers.tech/) Web Developer Bootcamp, it involved delivering a team project from scratch in two weeks. I drove the specification of the project and was heavily influential in its design and architecture.

TikTok is an original and creative new media format, but not all the content on the platform is suitable for a young audience. Chronomy lets you create a safe, curated playlist of TikToks that are age-appropriate to be shared safely.

The app consists of a Ruby on Rails backend, deployed automatically to [Heroku](https://chronomy.herokuapp.com/), and a React frontend, hosted on [Surge.sh](http://chronomy.net/).

The app is deliberately locked down to avoid inadvertent sharing of unscreened content. An example shared playlist, optimised for mobile viewing, can be viewed here:  
http://chronomy.net/view/18dc1213-07f2-4b43-9c4f-c254d71796bf

Playlist URLs are deliberately long to avoid accidental discovery of other users' playlists, since different people will have different standards of what they consider suitable.

The backend repository can be found here:  
[https://github.com/will-head/chronomy-api](https://github.com/will-head/chronomy-api)

The frontend repository can be found here:  
[https://github.com/will-head/chronomy-web](https://github.com/will-head/chronomy-web)

To see the app in action, click the video below:  
[![Chronomy Demo](../images/chromony-demo.jpg)](https://vimeo.com/fixationvideo/review/435076687/a701c1fcbe)

### Video for Events website

![Video for Events website](../images/vfe-home.jpg)

[Video for Events](https://videoforevents.co.uk/) is a single page website running on Wordpress with a heavily customised theme.

It's fully responsive, so suitable for both desktop and mobile visitors and adheres to modern web standards.

In order to ensure fast load times, it employs intelligent caching and is served via [Cloudflare's](https://www.cloudflare.com/) global CDN.

It includes a web application firewall to protect against malware attacks.  

![Video for Events responsive view](../images/vfe-responsive.jpg)

### Personal Travel Planner

I have a Computer Science degree, so I've always turned to my coding skills to solve a problem or scratch an itch.

One such project was a custom bus and train time display for my office.

We moved to a location that was served by two different bus routes and a train station, so I used the [Transport API](https://www.transportapi.com/) web service to get the latest real-time bus and train times and then calculate which I should use, based on walking distance to the stop and how long the journey would take.

I then re-purposed a [Slimp3](http://wiki.slimdevices.com/index.php/SLIMP3) MP3 player with a wonderful VFD screen that could display RSS feeds and hacked it to display a rolling personal timetable. I also had to implement caching to ensure I didn’t exhaust the daily limit of API calls you’re allowed on a free account.

To see a demo of my Personal Travel Planner, click the video below:  
[![Personal Travel Planner Demo](../images/personal-travel-planner.jpg)](https://vimeo.com/fixationvideo/review/388454390/dbecd29d99)
