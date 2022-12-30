Programs and Equipment I Use | Luke's Webpage 

[Programs and Equipment I Use<br>============================](/)

After many requests, here are the programs I use for everything. I'm only putting here programs I consider tried and true and have used for a while.

Software I Use
--------------

### Priorities

I'm about getting things done quickly and having as little space between my thoughts and actions on the computer.

I like having vim-like bindings and prefer running programs in the terminal for simplicity's sake. That said, I'm very much against the cringey meme that things in the terminal are "cooler" or "nerdier" XD. Terminals are good for most tasks, but useless for others, for example, browsing the modern web (I admit this unfortunate fact with much consternation) or looking at maps or images or modifying videos by NLE. I do do some image/video editing with `imagemagick`/`ffmpeg`, but only simple, repetitive tasks.

### Basic

Operating System/Distribution

I use Artix Linux ([vid](https://www.youtube.com/watch?v=SVc6n5aOzy0)/[site](https://artixlinux.org/)) which is a fork of Arch Linux except for without systemd. You can see some of my reasons for using Arch-based distros [here](https://www.youtube.com/watch?v=6bsNIdYw5Ak). Linux distributions are generally not distinct enough to have strong feelings about, hence the reason I only rarely care to talk about them. [You can see my opinion on Linux distributions generally here.](https://www.youtube.com/watch?v=3zpgQpdy_fI)

Terminal

I use st ([vid](https://www.youtube.com/watch?v=9H75enWM22k)/[download](https://github.com/lukesmithxyz/st)) (simple terminal) by [suckless.org](https://suckless.org), which is one of the most minimal, yet easily customizable terminal emulators out there.

Shell

I use [zsh](https://www.youtube.com/watch?v=eLEo4OQ-cuQ) as a shell. It has pretty much all of the features of bash with additional plugins for more advanced auto-completion and syntax coloring.

Window Manager/Desktop Environment

dwm ([vid](https://www.youtube.com/watch?v=xnREqY-oyzM)/[download](https://github.com/lukesmithxyz/dwm)). If you want to know "why my computer looks like that", this is what to check out. The status bar I use for dwm is dwmblocks ([vid](https://www.youtube.com/watch?v=UP2QpHmcgyk)/[download](https://github.com/lukesmithxyz/dwmblocks)). Note that in order to run my builds of dwm/dwmblocks, you need to install libxft-bgra until a patch is merged into libxft on the upstream.

Text editing and programming

[vim](https://www.youtube.com/playlist?list=PL-p5XmQHB_JSTaEPygu1DZjuFfb704Uv7). Less of a text editor and more of a lifestyle. No, I'm not going to ever switch to emacs. Technically I use neovim nowadays, but it's all the same.  
  
[A full overview/tutorial of vim and vimtutor for new users.](https://www.youtube.com/watch?v=d8XtNXutVto)

Web browser

Firefox with the [arkenfox user.js](https://github.com/arkenfox/user.js) (with some modifications). Note that while Firefox is a free software browser, it comes with [a multitude of trackers](https://spyware.neocities.org/articles/firefox.html) and other annoying "features." A custom user.js file like the one linked above removes all the trash and allows you to customize the browser to be usable and private. I often recommend the following add-ons:

* [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
* [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
* [VimVixen](https://addons.mozilla.org/en-US/firefox/addon/vim-vixen/)
* [I don't care about cookies](https://addons.mozilla.org/en-US/firefox/addon/i-dont-care-about-cookies/)
* [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

### Utilities

File manager

[lf](https://github.com/gokcehan/lf). In most of my older videos, I'm using [ranger](https://youtube.com/watch?v=nlolvAVqn10g) which was the original model for lf, albeit written in Python and somewhat sluggish.

Mail client

neomutt [\[1\]](https://youtube.com/watch?v=2U3vRbF7v5Ag) [\[2\]](https://youtube.com/watch?v=0MiP1Ei_UQwg). I keep all my mail offline with isync. Setting up the perfect terminal-based offline email system can be difficult, so I made [mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard) for you and me to make it easy.

Music/audio player

[mpd with ncmpcpp](https://youtube.com/watch?v=sZIEdI9TS2Ug) for a library, mpv for playing songs manually when I select them in lf. I also occasionally use `beet` for music tagging and organization.

Video player

mpv. Don't bother with any other video player. The only reason I've never done a video on mpv is because all the cool kids already use it.

RSS reader

[newsboat](https://www.youtube.com/watch?v=dUFCRqs822w). I've never subscribed to YouTube channels or Twitter accounts or anything else. You can simply give accounts' feeds to newsboat and watch videos remotely via mpv without having to open a browser.

Torrent client

Transmission, with the transmission-remote-cli as an interface.

### Production

Video and Audio

ffmpeg is the tool I use to [record all of my screencasts](https://www.youtube.com/watch?v=386Z2yeQ5fo), and also splice and combine all of the video and audio when needed. I sometimes used Blender for making videos which would require NLE, but I always begrudged it. If you're a novice at video editing, kdenlive would probably be better. In general, I never do any video editing, so ffmpeg is enough.

Writing documents

I used to write documents in either [R Markdown](https://www.youtube.com/watch?v=4J5a0JWIF-0) or [(Xe-)LaTeX](https://www.youtube.com/playlist?list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T) and compile them into either pdf documents or presentations after that. In some videos, I've also used the [vim-live-latex-preview](https://github.com/ying17zi/vim-live-latex-preview) for automatic LaTeX/XeLaTeX compilation. I've also used pandoc for document conversion and compiling markdown to .pdfs. Of course if you've been watching my channel recently, you know I've been experimenting with [groff/troff](https://www.youtube.com/playlist?list=PL-p5XmQHB_JRe2YeaMjPTKXSc5FqJZ_km) to much success and recommend it as a much more minimal and elegant typesetting system, scarcely lacking anything you might need, although lacking documentation, so it'll probably be a jungle at first.

Presentations

[suckless sent](https://www.youtube.com/watch?v=aCLCl96eNaI) is my new favorite presentation software, which creates a presentation immediately from a plain text file. Barring that, and especially for academic presentations, I use [LaTeX Beamer](https://www.youtube.com/watch?v=zEjBCQhND2c) which you can also [compile from markdown via pandoc](https://www.youtube.com/watch?v=dum7q6UXiCE). I find presenting without software is usually the best in normal circumstances.

Excel-like spreadsheets

[sc-im](https://www.youtube.com/watch?v=K_8_gazN7h0) for when I need a very visual interface, but I generally use [R](https://www.youtube.com/playlist?list=PL-p5XmQHB_JQlsPHtcxNWpvDudyoWB2kH) for the things one typically does in a spreadsheet. Most things you need and excel-like program for can just be done with your core utilities.

PDF viewer

[zathura](https://www.youtube.com/watch?v=V_Iz4zdyRM4). I used to use mupdf, which is good too. Check out that video for zathura's big benefits though.

Image Viewer

[sxiv](https://www.youtube.com/watch?v=GYW9i_u5PYs). Handles images, animated gifs, has additional thumbnail and slideshow modes and allows you to run custom scripts and read/write to standard input/output. Okay. This is epic.

Image modification

[GIMP](https://www.youtube.com/watch?v=5m8Oaz8XWVI) for big things, but imagemagick commands for most little modifications, filter changes, trims, etc.

### Cryptocurrencies

There really aren't that many good programs for using cryptocurrencies, but here is what I use.

Bitcoin

Electrum.

Monero

The standard monero-cli.

Trading

[Bisq](https://bisq.network), decentralized exchange which uses Tor out of the box.

Where can I find good software options?
---------------------------------------

The program of your dreams is probably listed below:

* [The suckless website's list of programs that "rock"](https://suckless.org/rocks/) – Generally minimalist programs
* [A more comprehensive (and gradient) list of minimalist software](https://github.com/mayfrost/guides/blob/master/ALTERNATIVES.md)
* [The FSF's Free Software Directory](https://directory.fsf.org/wiki/Main_Page) – Emphasis on libre software (although most software in the links above will have free licenses as well)
* [Install Gentoo wiki recommendations](https://wiki.installgentoo.com/index.php/List_of_recommended_GNU/Linux_software) – A good mix of programs for novices and advanced users

Hardware I Use
--------------

Laptop

The main laptop I use is a Thinkpad X220, released in 2011. I bought mine used on eBay for $90, and it included the ThinkPad Ultrabase, which I use at home daily (it can also hold an extra hard drive and I have a 2TB one inside). Old ThinkPads are designed for long term corporate use, and last forever and are made to be easy to repair and improve. They have many simple perks, like their uniquely tactile keyboards, their trackpoints and their ThinkLight (a more commonsense solution to lighting your keyboard at night). Newer ThinkPads are not as good, lacking the classical keyboards and generally being more Mac-like (unrepairable, breakable, and generally bad for an enormous price). My X220 ThinkPad was [Corebooted by tripcode!Q/7](https://www.youtube.com/watch?v=zV1f8raveZo).

Hard drives

I own two Solid State Drives (SSDs), one for my main laptop (1TB) and one for my desktop OS (512GB). I think they're both "Crucial" brand. SSDs are the only thing I recommend using a good bit of money on in your computer build. They make your computer hugely snappier and apparently use less power.

Peripherals

I use a [Unicomp Endurapro](https://www.pckeyboard.com/page/product/UB40PGA) which is a classic-style buckling spring keyboard like the old beloved IBM Model Ms, but also with a trackpoint to use as a mouse. I do not own or use a mouse aside from this.

Microphone

I record most of my videos with a Blue Yeti, which seems to be the dominant model on YouTube generally. I can't compare it to other microphones, but it does the job.

Webcam

Logitech C920. I can record audio decent enough too, although the Yeti is better. This webcam is passable for a small face in a portion of the screen, but is nothing special.

What I don't use
----------------

Proprietary software

It's sort of weird that my channel has gotten large enough that a huge slice of my viewership has missed one of the main points of my channel: the use of only libre software. I will not recommend, review or test out proprietary software. I'm not going to do a video on how to "rice" Google Chrome, I'm not going give you Linux hacks for Slack or Steam. I'm especially not going to endorse proprietary services that have gone out of their way to spy on or politically suppress their users, just as Discord or Amazon. One of the many potential take-aways you should get from my channel is that the use of libre/free software, by its nature, is more constructive and extensible—that's the point. There are philosophical reasons for this you'll run across in time, but for now, suffice it to say I will not support the usage of non-free software.

emacs

Emacs has little purpose for people who use tiling window managers like I do. Emacs is also enormous, and for someone like me who often is in the habit of using my text editor to open just one file, it's massive overkill and a massive drain on time. My movement in my computer usage has been constantly gravitating to more and more lightweight and minimal programs, getting closer to the core of how Unix-based operating systems work, using emacs on top of things to replicate the functionality of my current setup violates this tendency. Everything I've ever needed to do, I can do perfectly well between vim and my WM.

A cell phone

Don't get me wrong, I own a cell phone, I just don't use it or carry it around or endorse cell phone usage generally. I use it as a house phone... except for I don't have reception at my house 😉. I can't think of a single thing that is more highly correlated with personal mediocrity more than cell phone usage. If you do use one, be sure to install [F-Droid](https://f-droid.org/), which is a application manager for free software programs, and use applications from that. I have [GrapheneOS](https://grapheneos.org) installed and have no Google applications. If you want to install GrapheneOS or another free software OS on your phone, remember to get a compatible phone that is _unlocked_.

[![](/pix/apps.png)](/pix/apps.png)

These are the apps I have on my phone.

GrapheneOS also comes with only few stock apps, which is nice. Those you don’t need can be disabled with `adb`.

Read related articles:  
[Linux](https://lukesmith.xyz/tags/linux) · [Tutorial](https://lukesmith.xyz/tags/tutorial) · [Software](https://lukesmith.xyz/tags/software) · [Technology](https://lukesmith.xyz/tags/technology)

  

[https://lukesmith.xyz](https://lukesmith.xyz)

![](/pix/btc.svg)Bitcoin ([QR](/pix/btc-logo.png)): `bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y`  
![](/pix/xmr.svg)Monero ([QR](/pix/xmr-logo.png)): `48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh`

[![RSS Feed](/rss.svg "Subscribe via RSS for updates.")](/index.xml)
