#First IOS App
##App that displays book list from apigee seminar

Thanks for coming out to the Apigee mobile app trainings in Boulder this week!

#####Stay in touch
[Google Group for attendees:](https://groups.google.com/forum/?fromgroups#!forum/app-craft) Please subscribe to the group and don’t hesitate to start a conversation if you have any questions about building apps, or if you want to show what you’re building!
[Explore advanced Apigee features:](http://apigee.com/docs/app_services) (geolocation, push notifications, social sharing, file storage, groups, counters, etc.) — we also have different platform features if you need API Management, Mobile Analytics, etc. You can learn more about this and how to deploy this technology at your company at http://apigee.com/

#####Slides
[You can access the slides for the HTML5 training here:](https://www.dropbox.com/s/ct5f8urjr4pybdz/Build%20A%20Mobile%20App%20.pdf)

Notes
------
* data-roles are important when building with jQuery mobile ui.

* Must always have data-role='page' and inside of that data-role='content'

* data-rel for dialogs

* data-transition to do nifty transition effects between "pages"

* to create app:

```

$ phone gap create 'myApp' 'com.apigee.myApp' MyApp
```

* to build app:

```
$ phone gap local build [platform]
```

* Have local builds of css to include with build
