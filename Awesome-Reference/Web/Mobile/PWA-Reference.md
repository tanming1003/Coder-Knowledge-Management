
# Progressive Web Apps Reference

本文是 Progressive Web Apps 开发中搜集的一系列有价值的参考资料，关联父引用为 [Web Reference](http://6me.us/gUmQ)。



# Overview


- [Why Google Thinks You Should Start Building Progressive Web Apps](https://arc.applause.com/2016/05/24/progressive-web-apps/)
- [Progressive Web Apps with React.js【Series】](https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-i-introduction-50679aef2b12#.178womihv): Progressive Web Apps take advantage of new technologies to bring the best of mobile sites & native apps to users. They’re reliable, fast, and engaging. They originate from a secure origin and load regardless of network state.
- [Google Developers - Your First Progressive Web App](https://developers.google.com/web/fundamentals/getting-started/your-first-progressive-web-app/?hl=en) : A step-by-step guide to building a progressive web apps using the app shell pattern.
- [Building Progressive Web Apps - O'Reilly Media](https://pwabook.com/oreillyapwa) : A deep dive into progressive web apps, service workers, push notifications, background sync, IndexedDB, offline first and much more (disclaimer: written by the maintainer of this page).
- [A Beginner’s Guide To Progressive Web Apps](https://www.smashingmagazine.com/2016/08/a-beginners-guide-to-progressive-web-apps/): Progressive web apps could be the next big thing for the mobile web. Originally proposed by Google in 2015, they have already attracted a lot of attention because of the relative ease of development and the almost instant wins for the application’s user experience.


## Case Study
- [PWA.rocks](https://pwa.rocks/): A showcase of several progressive web apps, collected by the [Opera Dev Relations team](https://twitter.com/ODevRel).
- Sample APPs: [SVGOMG](https://jakearchibald.github.io/svgomg/), [Guitar Tuner](https://aerotwist.com/blog/guitar-tuner/), [Voice Memos](https://voice-memos.appspot.com/), [Hacker News](https://react-hn.appspot.com/), [Building the Google I/O 2016 Progressive Web App](https://developers.google.com/web/showcase/2016/iowa2016) 
- [AliExpress Case Study](https://developers.google.com/web/showcase/2016/aliexpress) : AliExpress increases conversion rate for new users by 104% with new progressive web apps.
- [eXtra Electronics Case Study](https://developers.google.com/web/showcase/2016/extra) : United eXtra Electronics grows eCommerce sales by 100% with Web Push Notifications.
- [Jumia Case Study](https://developers.google.com/web/showcase/2016/jumia) : Push Notifications help Jumia reverse cart abandonment and increase conversions by 9X.
- [Konga Case Study](https://developers.google.com/web/showcase/2016/konga) : Konga cuts data usage 92% with new Progressive Web App.
- [Suumo Case Study](https://developers.google.com/web/showcase/2016/suumo) : Japan's top real estate site supercharges new listings with web Push Notifications and sees a 31% open rate for notifications.
- [《百度搜索对PWA的探索和初步实践》](http://6me.us/JS85s): 本文是百度搜索资深Web前端工程师沈洲在前端之巅微信群中的分享整理总结而成，介绍了百度天气 PWA 应用的开发实践，本周还分享了[《PWA 实践：从一个简单的页面开始》](http://6me.us/Ik5k1L)与[《PWA实践：理解和创建 Service Worker 脚本》](http://6me.us/P5cB)等 PWA 相关内容 。(http://6me.us/JS85s)

## Tool

- [2017 - Progressive Web App Libraries in Production](https://medium.com/dev-channel/progressive-web-app-libraries-in-production-b52cad37d34#.z5egf9m7v): This article is written by Addy Osmani. Two years ago, our team at Google started work on JavaScript libraries to reduce the friction for building Progressive Web Apps.
- [Manifoldjs: PWA Builder](http://6me.us/hx5JS): PWA Builder will give you an easy way to provide the missing pieces of your PWA, and not weigh down your site with data you don’t need or use.
- [Offline-plugin for webpack](https://github.com/NekR/offline-plugin): This plugin is intended to provide an offline experience for webpack projects. It uses ServiceWorker, and AppCache as a fallback under the hood. Simply include this plugin in your webpack.config, and the accompanying runtime in your client script, and your project will become offline ready by caching all (or some) of the webpack output assets. you can also turn to  [Easy Offline First Apps With Webpack's Offline Plugin](https://dev.to/kayis/easy-offline-first-apps-with-webpacks-offline-plugin) for further information.
- [RealFaviconGenerator](http://realfavicongenerator.net/): A great way to generate all the images, favicons, and associated files needed to display your app icon across different browsers.
- [Android Asset Studio - Launcher Icon Generator](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html): Generate Android style icons.

# Offline Storage

- [2016 - Offline Storage for Progressive Web Apps](https://medium.com/@addyosmani/offline-storage-for-progressive-web-apps-70d52695513c) : The current state of offline storage in the browser
- [IndexedDB API](https://developer.mozilla.org/en/docs/Web/API/IndexedDB_API) : API docs, key concepts, and sample code from Mozilla.
- [CacheStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Cache) : API docs, and sample code from Mozilla.


# Service Worker
- Service Worker Support in Browser: [Can I Use - Service Workers](http://caniuse.com/#feat=serviceworkers), [Is Service Worker ready?](https://jakearchibald.github.io/isserviceworkerready/)
- [2017 - Send messages when you’re back online with Service Workers and Background Sync](http://6me.us/IrTKkz): When you send an SMS message but your phone doesn’t have great signal it will continue to try to send the message in the background, even if you close the app. Pretty useful right? In this post we’re going to see how to replicate this behaviour in a web application using the Background Sync API from the Service Worker.
- [Awesome Service Workers【Collection】](https://github.com/TalAter/awesome-service-workers) : A collection of awesome resources for learning service workers.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) : This free Udacity course is a must if you're planning on building a progressive web app.
- [Service Workers W3C Specification](https://www.w3.org/TR/service-workers/) : The official service workers spec.
- [Introducing Background Sync](https://developers.google.com/web/updates/2015/12/background-sync) : A gentle introduction to background sync, along with some great videos and code samples.
- [Background Sync Explained](https://github.com/WICG/BackgroundSync/blob/master/explainer.md) : The official "explainer" document for background sync, including one-off synchronization and periodic synchronization.
- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) : The WIP spec for Background Sync.



# Installable Web App
- [Increasing Engagement with Web App Install Banners](https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android?hl=en) : An intro to App Install Banners and making sure Chrome offers your web app to your users.
- [Installable Web Apps with the Web App Manifest in Chrome for Android](https://developers.google.com/web/updates/2014/11/Support-for-installable-web-apps-with-webapp-manifest-in-chrome-38-for-Android): An introduction to installable Web Apps in Chrome for Android.

# Push

- [Can I Use - Push API](http://caniuse.com/#feat=push-api) : Up-to-date browser support table of Push API.
- [Chrome Platform Status - Web Notifications](https://www.chromestatus.com/feature/5480344312610816) : Implementation status for Chrome and other browsers.
- [PWA Dev Summit 2016 codelab - Push Notifications](https://developers.google.com/web/fundamentals/getting-started/push-notifications/?hl=en) : Up-to-date getting started tutorial for Progressive Web App, Push Notifications and service worker basics.
- [Using the Push API](https://developer.mozilla.org/en-US/docs/Web/API/Push_API/Using_the_Push_API) : An article introducing Push API.
- [web-push-libs](https://github.com/web-push-libs) : A collection of useful libraries for web push in different technologies (Node.js, PHP, Python, etc.)
