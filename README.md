# init
let's get init
====

These are the reasons why I get frustrated using yours or anyone else’s computer. I would find it very hard to live/work/eat/sleep/compute without these apps. 

Let's ease in with some starting commands (some people call it a dot file. whatever).

#Humble thy dock.

`defaults write com.apple.dock static-only -bool TRUE; killall Dock`

#Apps shouldn’t hide from me

`defaults write com.apple.dock showhidden -bool TRUE; killall Dock`

#But the dock shelf should stay hidden. 

`defaults write com.apple.dock autohide-time-modifier -float 1; killall Dock`

 

**The meaty stuff:**

`xcode-select –install`

`ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)” `

`brew install git gcloud python mysql elasticsearch neo4j awscli swift node cask && brew cleanup `

`brew update && brew cask install bettertouchtool expandrive  istat-menus littlesnitch arq google-drive adobe-creativecloud sublime-text keka virtualbox vmware-fusion dash airflow omnigraffle microsoft-office paw app cleaner folx android-file-transfer  android-studio macaw sip tor winclone -appdir=/Applications`

`brew update && brew doctor`

 

**Better Touch Tool-** I put this on top because it is the only app I can say has changed my life. I don’t know where I’d be without BTT. Allows you to set highly customised multitouch gestures on the trackpad, mouse, plus keyboard shortcuts plus window snapping, + everything amazing., and more 

**Snappy App - **The best screenshot app ever. It has limited functionality, is unobtrusive, and focuses on one thing great. Have been using this for years that my snaps library synced over multiple computers / profiles is in the 3000s 

**Affinity Designer - **an indie graphic design app that merges vector and bitmap. A cross between Illustrator and Photoshop and not as dating.

**Airflow** - cast media on your computer to chrome cast, free!

**Astropad**- recently fell in love with this app that lets me use my ipad as a full resolution pressure sensitve touchscreen.

**Command One Pro **- if i’m spending a long time on a server doing file stuff I far prefer using an app with a GUI. I’m so bored of terminal.

**Enpass** & **Keepass** & **Hider 2** - Encryption / Keychains cloud synced 

**Air Radar **- A secondary wifi app that will help you find the best wifi networks and optimise the network your connected to. This is essential for traveling.

**Alfred 2 **-This is spotlight (cmd+space) on steroids. 

**AppCleaner** - Deletes most (not all) of an app you’re trying to uninstall. Only really does a quick search but gets the job done for most things.

**Adobe Creative Cloud** - Because after effects.

**Dash**- Local software manuals for when I don’t feel like sifting through hundreds of StackOverflow threads to find the answers like the correct RSYNC procedure or something minor. (every time).

**Amazon Cloud Drive** - Ridiculously cheap (free this year!) unlimited cloud storage. Within a matter of 2 weeks i’ve backed up everything multiple times. Have patience though, must use AWS glacier because upload / transfer times are horrendously slow.

**Arq** - Extremely robust and secure cloud backup. like time machine but instead of a local drive you can use Amazon Cloud or Google Drive or Dropbox et cetera. Big perk is the Backblaze cloud storage integration. B2 is so cheap and cheerful I just can’t deal!

**Atom** - Code editor with great plugins but can be quite slow.

**Beamer**- Another Chromecasting app in case airflow doesn’t work

**Blocs** - Dead simple webpage maker with drag and drop. Good for sketching draft website / business ideas and, surprisingly, information design. Because it’s so pared back with features it forces you to focus on the content instead of getting caught up in the the fiddly design bits. Wouldn’t use in production environments.

**Dropbox** - Mainly use for preferences sync, quick webhosting, secure sync, and public folders

**Ember** - screenshot tool that lets you annotate and share snaps quickly. I’m trailing this one out to compare it to snappy app

**Android File Transfer** - for my phone. Mainly for the drivers to debug / reinstall / upgrade my android over usb.

**Expandrive**- menu bar app that lets me mount any of my cloud drives (Google Cloud, Google Drive, SFTP, AWS, Digital Ocean, Rackspace, Dropbox, OpenStack Swift, you name it. Mount the cloud service and all of your files show up as if you just inserted a USB with them. Let’s you visually sift through your cloud drives without dealing with horrible web interfaces or downloading all the lies. it only downloads the metadata for finder search integration.

**Folx **- Download manager that is literally 10x faster than the download utility in chrome. Essential for big downloads that you need to start and restart

**Google Drive **- file sync. Let’s be honest. If i could sync my mind with Google I would 

**IconJar** - Organises all of the icons on your computer to use quickly in designs. 

**iStatMenus** - These are the graphs and data in the menubar that let you know at a glance your system performance. I need this because a lot of my applications use a lot of system resources and I have to keep an eye on it in case the computer overheats and shuts itself off, runs out of memory, or doesn’t have diskspace left. 

**Pacifist** - Because System integrity protection can be annoying and because downloaded files may not be the safest.

**Reeder** - Beautiful RSS

**SiteSucker**- Does what’s on the tin - really really fast and can scale for big sites.

**Hype 3** - very interested in this web animation toolkit. Really has potential.

**Google Adwords **- for batch editing Google Adwords campaigns.

**Pixelmator**: I don’t use it really, i think i was grandfathered into it from a bundle i bought or something. Not the biggest fan but it’s not terrible.

**Keka** - a decompression tool that is open source and miles better than the one built in to OSX. It ‘unzips’ more types of files as we’ll as compress files more efficiently than the built in one.

**Sketchbook Pro** + **Mischeif** + **Astropan** drawing / tablet apps 

**Little Snitch** - monitors all network requests in and out of the computer and will allow you to pick and choose what goes out on the web. This is an easy way to be malware free, it also helps keep a few installed applications from phoning home to check registration. ;-)

**Macaw** - The best WYSIWYG web design / prototyping tool I’ve ever used. I use it to mock up websites quickly and test out different ideas. Generally lightweight and easy to use. Is a bit too clunky for web development production environments that require a CMS but can spit out better, more effecient code than I  can for smaller, quicker projects.

**Omnigraffle Pro** - Hands down the best diagramming, workflow design, mind mapping and general purpose business information graphics program ever made. 1,000X easier to use than Visio - and I love Viseo. 

**Omniplan** - Same company as above, but the Project Planning app. I’m trying this one out, not sure how I feel about project planning software but I figured I should learn the basics.

**Omnioutliner** - Same company, spot the trend? This app is great for focused writing outlines and overviews. Amazing multipurpose, i typically outline here first my ideas, then diagram them in omnigraffle.

**Microsoft Office 360**- Because there are many imitators but nothing can best Excel.

**Paw**- Brilliant REST application for API testing, so many features but not overwhelming. Design an API call / function in no time at all. Allows saving of different cookie ‘jars’ so you can run multiple projects and varied enviornment tests at once. The export functionality is convenient, though of course you’ll need to do a lot of manual editing.

**Server** -Mac OSX Server for local hosting dynamic websites and generally to see what the hell Apple is actually doing in the business world…

**Sketch + Toolbox** - Only recently getting into this app, i like its simplicity. Sometimes I just don’t want to open up Illustrator which feels like a cow next to this quick app. Toolbox helps keep plugins updated directly from their github master. 

**Snappy App** - The best screenshot app ever. It has limited functionality, is unobtrusive, and focuses on one thing great. Have been using this for years that my snaps library synced over multiple computers / profiles is in the 3000s 

**Sip** - The worlds best color picker. I thought i would hate the drip sound it makes when capturing colours but I’ve grown to love, almost anticipate it.

**Sublime Text** - Atom ripped off this text/code editor with package control. Very lightweight and snappy, prefer this to change quick bits in code documents or If I need to do a lot of manual editing of repetitive tasks. There is no other ‘find / replace all’ in any other app I’ve tried, it’s like magic watching it do it’s thing.

**Tor** - it’s so much better than it used to be, is based on firefox, and lets you install adblock +. I use this when I’m watching my back or just feel generally paranoid. I would make it my primary browser except that i like the convienve of all the tracking. Also, it’s really annoying that cloud flare has a vendetta against Tor users, nearly every time I go to a site with cloud flare dos I have to fill out an impossible captcha. 

**Transmission**: Lightweight bit torrent + agent client that doesn’t have ads.

**VMware Fusion** - Run Windows / Linux virtual machines, fast booting, robust features. Also really helpful to use to boot up a second instance of OSX with vmware as strong sandbox to test reliability and security of a newly downloaded app.

**IconJar**: For moving around Windows Partitions and Bootcamp partitions without loosing my mind.

**Virtualbox**: same as vmware fusion, but far more configurable and way more easy to fuck up. I typically will create my Virtual Machine here in virtual box and then import it into VMware to bypass the huge minimum machine sized vmware has. 

