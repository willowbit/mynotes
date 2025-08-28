---
title: "How to Use the Internet: A Friend's Guide"
date: 2025-08-16
---
First Draft

**Table of Contents**
- Introduction
- Starterpack
- Guide
	- Let's talk browsers
	- Search Engines
	- Extensions
		- Adblockers
		- Password Managers
		- Mmmmm... Cookies
- Get started with...
	- DuckDuckGo
	- Librewolf

## Introduction

Chances are, if you find yourself bombarded with ads, clicking on the wrong links, and having AI-slop shoved in your face, you're using the internet the correct way. At least, the way companies like Google, Meta, and Microsoft want you to use it: in their best interest, not yours. This isn't news to anybody, but what is news is that **there is a better way to use the internet**. A way that makes it private, secure, and fun! All at the same time!

In this guide, I'm going to explain the tools I use (and trust) to keep my web-browsing experience quick, clean, and private. I've added footnotes and more detailed explanations at the bottom to make things as detailed as possible, so I hope you will give it a chance and make your web-browsing a lot more pleasant!

There are three main components that make up your web-browsing experience. First we'll look at the browser, the app that allows us to open and look at websites. Second we'll look at search engines, which help us find websites and access information. Finally we'll end with browser extensions, which can modify our browser's functionality.

By altering or switching out any of these three components, we can make web browsing straightforward, private, and secure. Let's do it!
## Starterpack

In a rush? Here's are my top recommendations. If one of these doesn't work for you, read below for alternatives.

- Web Browser: **Librewolf**
- Search engine: **DuckDuckGo**
- AdBlocker: **Ublock Origin**
- Password manager: **Bitwarden** (browser extension + mobile app)

## Let's talk browsers

**My Recommendations (ranked)**

1. Librewolf
2. Waterfox
3. Ungoogled-Chromium

**Background**

> [!warning] Despite what online privacy guides recommend, DO NOT USE BRAVE! Brave is a private and for-profit browser. It is also notorious for a lot of gross cryptocurrency stuff. Also, the CEO sucks. Don't use it! ([More Info](https://www.spacebar.news/stop-using-brave-browser/))

There are only two notable base browsers: Chrome and Firefox. Most other browsers (Opera, Edge, Librewolf) are just slight variations of either Chrome or Firefox (called "forks"). However, these small changes can mean a lot for privacy and web experience. **Firefox is usually better for both performance and privacy.** However, generic Firefox still comes with some creepy code and a weird privacy policy. Because of this, I recommend using a Firefox fork such as **Librewolf** (the gold standard at the moment) or **Waterfox**.

If you must use a Chrome-based browser (I highly recommend you don't!) I recommend **ungoogled-chromium**, which is basically Chrome but without all of Google's icky stuff + extra privacy enhancements.

**Why?**

I placed Librewolf over Watefox because it comes with my adblocker and search engine already installed. It also has more strict privacy settings turned on by default, while Waterfox focuses more on usability, which makes Waterfox a good fallback if you are having trouble with Librewolf. (Just remember to install uBlock!) Finally, I included ungoogled-chromium for those who need a Chrome fork for compatibility reasons.

>[!info] What about Opera? Opera is a chrome-based, closed-source[^4], for-profit browser owned by a chinese company. It is popular for its free VPN (see my note on VPNs) and built in ad-blocker. Privacy-wise, it is not an upgrade over Chrome. Because of this, I do not recommend it.

>[!info] Firefox is still a huge upgrade over Chrome, so if you're deciding between the two, choose Firefox!
## Search Engines

>[!info] DuckDuckGo and Startpage are pretty much equally as private, so choose whichever one you like the best. I just happen to like DuckDuckGo, so I ranked it first.

**My Recommendations**
1. DuckDuckGo
2. Startpage

While a web browser allows you to access things on the internet, a search engine helps you find the websites you're looking for. Examples of search engines are Google, Yahoo, and my recommendation, **DuckDuckGo**.

DuckDuckGo does what a search engine is supposed to do: give you websites that match your search. Like other search engines, it has some ads, but these are based on the content of your search and *not* your personal information. **If you install the adblocker I recommend below, uBlock Origin, you won't see ads at all!**

DuckDuckGo has an AI summary feature, but it can be turned off in just two clicks. It also has a mobile app. If you chose to use Librewolf as your browser, DuckDuckGo is already set as your default search engine.
## Extensions

Browser extensions are pieces of software that you layer on top of your web browser to give it extra features. For Firefox and other Firefox-based browsers, you can download them at https://addons.mozilla.org/. On Chrome and Chrome-based browsers, you can find them at https://chromewebstore.google.com/.
### Adblocking

>[!info] Google has blocked UBlock Origin in Chrome, hence why I recommend using the browsers listed above instead. To install it anyway, follow [this guide](https://www.tomsguide.com/computing/how-to-bring-back-ublock-origin-in-chrome-whether-youre-re-enabling-or-installing-it).

**My Recommendation:** uBlock Origin

**Having a good adblocker installed is probably the biggest step you can take to improve your web browsing experience and privacy.** Despite what Google tries to make you think, an adblocker is essential security software for the modern web. **I recommend UBlock Origin because it not only blocks ads, but creepy trackers as well.** It also warns you about suspicious websites, offering protection from viruses and malware.

If you're using a browser like Librewolf or Waterfox, it's installed by default, so you don't have to do anything! Otherwise, read how to install it [here]().
### Password Managers

**My Recommendation:** Bitwarden Password Manager

**Background**

Most likely the largest vulnerability in your web browsing right now is your passwords. You're probably using similar passwords for each of your logins, which leaves you open to being compromised. But it's not your fault!

Passwords are bad user design by nature. Luckily, there's a solution that makes signing into things super fast, and only requires memorizing **one password**. A password manager can autofill your login details extremely fast. It also handles generating new, secure passwords for your new logins. It does this all while being extremely secure, private, and convenient.

You might be feeling wary about giving a website *all* of your login information. But this is the zinger: by design, *you don't need to trust your password manager*\*. Password managers use a special encryption technology that allows only you to access your passwords. That "one password" I mentioned earlier is called the master password, and is used to decrypt your login information, so in reality, the password manager can't see a thing.

[This video explains it better than I can](https://youtu.be/w68BBPDAWr8), but back to the guide!

\* But, of course, you should choose one that seems reputable, which is why I recommend Bitwarden.

**Why Bitwarden**

The password manager I use and recommend is [Bitwarden](https://bitwarden.com/). Bitwarden uses all the cool encryption technology I described above and works great for everyday use, and it's free![^1] If you like using it, I recommend upgrading to the premium tier, which is only $1 a month (or $10 a year). The premium teir lets you use it for two-factor-authentication, meaning you never have to deal with those awful "one time passcode" texts when logging into services.

There are lots of other great password managers out there, just make sure you pick one that has a good reputation. My dad uses 1Password.

(Please, next to installing uBlock Origin, if there is one thing you take away from this guide, it should be installing a password manager! It will change your life, I guarentee it. You don't deserve having to remember a million passwords!)
### Mmmm... Cookies

So we've taken care of those annoying ads, made logging in a click away, but what about those annoying "accept cookies" popups? By law, websites need these to get your consent before collecting data about you, but they make it very hard to reject them. [Consent-O-Matic](https://consentomatic.au.dk/) takes care of this for you by atomatically selecting the most privacy-preserving option whenever prompted. Goodbye, cookies!
## Conclusion

Firstly, thank you for reading my guide! If any part was confusing, please let me know and I'll elaborate and update it. I made this guide because it hurts my soul to see my friends having bad internet experiences when I know it can be so much better, so I hope it made your life a little better. Here's to a fun, free, and private internet!
## Let's get started with...

So you've decided to pick up one of the recommendations in this list? Great! I've included some tips about getting started with each one.
### Librewolf

Congratulations on choosing Librewolf! To install it, visit the [Librewolf homepage](https://librewolf.net/).

By default, Librewolf has all of its privacy features turned on. If it works great for you, you don't have to change anything. However, there might be two things worth altering based on your preference.

1. By default, Librewolf deletes your browsing history when closed. To change this go to the menu dropdown (top right) -> Settings -> Privacy & Security -> uncheck "Delete cookies and site data when LibreWolf is closed" and "Clear history when LibreWolf closes"
2. Librewolf also has resist fingerprinting[^2] on (RFP), which you can learn about [here](https://librewolf.net/docs/faq/#what-are-the-most-common-downsides-of-rfp-resist-fingerprinting). In order to disable it, go to "about:config" in your address bar -> search for and set "privacy.resistFingerprinting" to false.

Check out the Librewolf [FAQ](https://librewolf.net/docs/faq/) for more tips!
### Waterfox

>[!info] I'm not as familiar with Waterfox, so this section is a work in progress.

Waterfox is a great, private browser based on Firefox. To install it, visit the [Waterfox homepage](https://www.waterfox.net/) Once you have it running, I recommend changing the search engine to [DuckDuckGo]() and installing [uBlock Origin]().

For questions about Waterfox, read teh [FAQ](https://www.waterfox.net/docs/faq/).

### Ungoogled Chromium

Ungoogled-Chromium is a great choice for staying private. For installation, download it [here](https://ungoogled-software.github.io/ungoogled-chromium-binaries/).
### DuckDuckGo

Decided to Go with DuckDuckGo? Good choice.

To set up DuckDuckGo on Firefox or a Firefox-based browser, [click here](https://duckduckgo.com/duckduckgo-help-pages/change-default-search-engine/firefox).

To set up DuckDuckGo on Chrome or a Chrome-based browser, [click here](https://duckduckgo.com/duckduckgo-help-pages/change-default-search-engine/google-chrome).
### Startpage

Startpage is a great search engine that will work with whichever web browser you choose. If you went with Waterfox, Startpage is already set to the default search engine.

To set up Startpage on Firefox or a Firefox-based browser, [click here](https://support.startpage.com/hc/en-us/articles/4480404660628-Make-Startpage-your-default-search-engine-in-Firefox).

To set up Startpage on Chrome or a Chrome-based browser, [click here](https://support.startpage.com/hc/en-us/articles/4480508968852-Make-Startpage-your-default-search-engine-in-Chrome).

---
[^1]: In general, I recommend always paying for services like this. (The saying goes, "if you're not paying for the product, you are the product.") However, I can attest in this case that using the free tier of Bitwarden is perfectly OK.

[^2]: Fingerprinting is a specific kind of tracking that profiles you based on your browser configuration.

[^4]: "Closed source" means that the app's computer code is private, meaning that users cannot check to see what it is doing under-the-hood. (The term for checking code for vulnerabilities or malicious intent is called "auditing")
