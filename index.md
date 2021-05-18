# ITG Resource Guide & FAQ
<img src="https://camo.githubusercontent.com/d4b0b5c3756bd5f6ae15d05992822186e645b75fae70e7bb3846be1a8e864a4d/687474703a2f2f692e696d6775722e636f6d2f6331477a764b582e6a7067" height=400px/>

There are a lot of great informational resources scattered around the ITG community and I wanted to throw them onto one page.

## What is In The Groove (ITG) in 2021?
Originally, [In the Groove](https://en.wikipedia.org/wiki/In_the_Groove_(video_game)) (ITG) was a 4-panel dance game created by Roxor Games based on the earlier (and much more popular) Dance Dance Revolution (DDR) game by Konami. ITG ran on a modified Stepmania 3.95 engine (an open source clone of DDR) and introduced features such as mines and hands and support for "mod charts". ITG was sold as a PS2 game, an upgrade kit for existing DDR cabinets, and as an ITG dedicated cabinet (dedicab). Shortly after ITG gained popularity, it got into [legal trouble](https://en.wikipedia.org/wiki/Konami_Corp._v._Roxor_Games_Inc.) with Konami and it went away in an official capacity. At this point in time, people refer to people who play Stepmania on a pad (as opposed to a keyboard) as "ITG".

Few play the original arcade games anymore, and the game has mostly moved to the home audience especially after the pandemic. Modern "ITG" is considered as Stepmania 5 or OpenITG running a theme such as [Simply Love](https://github.com/Simply-Love/Simply-Love-SM5), [Digital Dance](https://github.com/Hayoreo/Digital-Dance), or [Waterfall](https://twitter.com/SteveReen/status/1392057636518973442) using ITG's original lifebar and scoring mechanics.

There are several playstyles of ITG:
- FA
- Tech
- Stamina/Footspeed
## Installing ITG
<iframe width="560" height="315" src="https://www.youtube.com/embed/4ni-0b6fbCQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**TL;DR**
1. Download and install [Stepmania 5.0.12](https://www.stepmania.com/download/), [Stepmania 5.1 Beta 2](https://www.stepmania.com/forums/news/show/62871), or [ Project Outfox 5.3 Beta](https://projectmoon.dance/)
2. Get [Simply Love](https://github.com/Simply-Love/Simply-Love-SM5), [Digital Dance](https://github.com/Hayoreo/Digital-Dance), or [Waterfall](https://twitter.com/SteveReen/status/1392057636518973442) and put them in Stepmania's Themes folder
3. Switch to the theme in the "Appeance" section in the Stepmania options
4. You now have ITG!

**Some places to get songs**
- [The ITG packs release spreadsheet](http://itgpacks.com/) - Tracks all the latest ITG pack releases
- [ZiV's simfile page](https://zenius-i-vanisher.com/v5.2/simfiles.php) - DDR converts + some others

**Other Themes**
- [DDR XX Starlight](https://zenius-i-vanisher.com/v5.2/thread?threadid=10433) - Custom a fanmade DDR theme. Uses DDR timing and lifebar mechanics.
- [Simply Fantasy](https://github.com/jordando/Simply-Love-Tweaks/tree/fantasy) - Final Fantasy theme by Poog
- [GrooveNights SM5](https://github.com/JoseVarelaP/SM5-GrooveNights) -  Recreation of the classic 3.95 theme in SM5.


## What pad do I buy?

Dom has made a great video listing and reviewing many different pads.
<iframe width="560" height="315" src="https://www.youtube.com/embed/sEWj2_BNG_0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**TL;DR**
 - [L-TEK](https://www.maty-taneczne.pl/)
	 - Affordable hard pads, great for all around play. Suffers from weak arrow panels.
	 - The stock PCB only polls at 125 Hz, which makes timing more difficult. You can mitigate this by doing the [Arduino mod](https://www.instructables.com/Modifying-an-L-tek-Dance-Pad-to-Poll-at-1000hz-on-/) to make it poll at 1000 Hz.
	 - Do the [penny mod](https://youtu.be/hLlBETbFACA) for additional sensitivity, 
	 - The optional bar is not worth the money, it is wobbly and expensive. See [Roujo's bar building guide](https://roujo.toepi.moe/dance/bar-building-guide) on how to build your own for much cheaper.
 - [StepManiaX](https://stepmaniax.com/)
	 - These are high-end, arcade-grade pads but are extremely difficult to get due to low supply and high demand.
	 - If you play stamina, you might run into issues with triggering accidental decents/way offs ("the boys") due to the square arrow panels.
	 - These pads originally came with load cell sensors, which were unreliable and prone to breakage. Fourth generation and newer SMX pads use FSR sensors, which are much better than the load cells.
 -  Purchasing an arcade machine/pads is usually the best option if you can find one.
	 - Search Craigslist, arcade buy/sell Facebook groups, Kijiji, etc.
	 - Cabs can be converted to Stepmania fairly easily, see [JeffreyATW's Guide](https://jeffreyatw.com/blog/2019/08/how-to-convert-a-ddr-cabinet-for-stepmania/) here.
	 - Single pads can be converted to USB with either FSR's or a STAC Board.
 - DDRGame pads are not very good, but make a good base for FSR modding. If you can get one for cheap it might be worth picking it up.
 -  Precision Dance Pads are extremely unreliable and overpriced. These are not worth buying over any other option.
 - Baila-Tech are notorious for not shipping their pads. Buyer beware! 
 - Other pads like Anton's travel pads are good options too.
 
## DIY Pads
Lately, there have been tons of advancements in DIY pad building and people have made affordable pads that are easy to build and perform well.

**4199's Epic Velostat Pad (~$20)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/h3qDn847Iio" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This is a pad that 4199 made out of parts he had laying around. It's probably awful to play on but hella cheap and [he managed to pass a 20 on it, somehow.](https://youtu.be/9uK49TieQUQ)

**Plywood FSR Travel Pad (~$100)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y6wGYLE0YI4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Take a piece of plywood, slap some FSR's on it and call it a day. [yutsi](https://www.youtube.com/watch?v=mskaXrFsebA) is a stamina player who uses one of these and is able to pass 20's on it.

**Other pads I don't know much about:**
 - Dom has a [ten-part video series](https://www.youtube.com/playlist?list=PL2vUwLUVuyIy4CD8DEwS7oZ_Y41vyYWWy) on how he built a custom pad using used arcade parts. 
 - [Re:Flex pads](https://reflex.dance/) are an open source, arcade-grade pad created by Brittany.
 - [Mystic pads](https://docs.google.com/document/d/1mb6kjM13b7gjBU2B5ZLw1kvVDJ5bW0qdI1sw27WHaKk/edit?usp=sharing) are also an open source, arcade-grade pad made by Mystic aimed to cost around ~$1000.

## Pad Modding for Arcade Pads

Over the years, players have found many ways to make their pads perform better using various methods. Pad modding is an important part of ITG and modern charts are designed with pad modding in mind.

### Countersinking Brackets & Panels
If you find yourself getting caught on the big, bulky screws on the dance pad then you can convert your pad to use flatter screws by drilling the panels/brackets in order to fit countersunk ones.
<iframe width="560" height="315" src="https://www.youtube.com/embed/j1RiTrTW0-Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Another, simpler option is to simply remove your inner brackets and screws and attach your centre panel using double sided tape. This is incredibly lazy, but doesn't require you to use power tools or buy new screws.

### Using tape for increased sensitivity on arcade sensors
<img src="https://cdn.discordapp.com/attachments/591858300790767616/844251013955453018/103312533_285655112629603_214532263864403830_n.png" height=300px/>

- Arvin's guide: [https://pastebin.com/5gRirFNQ](https://pastebin.com/5gRirFNQ)
- teejusb's guide: [https://pastebin.com/7Ag3DpKk](https://pastebin.com/7Ag3DpKk "https://pastebin.com/7Ag3DpKk")

**TL;DR**
- Add gorilla and masking tape above the L bracket for height. 
- Add an insert below the L bracket for sensitivity. These are typically made by rolling a piece of tape over itself until the desired thickness is achieved.
- Leave just either the inner sensor or the two side sensors plugged in. (Relative to the centre panel)
	- Using side sensors typically give much more sensitivity than the inner sensor, which may be desirable for stamina.

### Converting an arcade pad to USB

There are many drop-in solutions for converting your arcade dance pad to USB. The best option in my opinion is TJ's STAC Board, which converts your pad to USB and also keeps light support.

Buy one here for ~$80: [https://icedragon.io/stac/](https://icedragon.io/stac/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/fDixsWEMUeA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Other options:
 - [GHETT.io](https://winbigarcade.com/product/ghett-io-dance-dance-revolution-pad-io/) for DDR pads ($37)
 - [BARR.io](https://winbigarcade.com/product/barr-io-pump-it-up-pad-io/) for Pump or ITG dedicab pads ($37)

### Converting the pad to use FSR sensors instead of arcade sensors
Many people have been converting their pads to FSR's, which are analog sensors you can hook up to an Arduino you can connect to your computer. They take some work to get setup properly but have many benefits.

There is a fair amount of technical knowledge required for FSR modding, and if you don't want to deal with it then I would suggest sticking to arcade sensors.

Text resources:
- VincentITG's [hardware setup guide](https://github.com/vlnguyen/itg-fsr/tree/master/fsr) 
- teejusb's [software guide and code](https://github.com/teejusb/fsr)

Video resources:
<iframe width="560" height="315" src="https://www.youtube.com/embed/MMHOwjYUisU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/uB9hqS_yGLc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Shoutouts

 - Lil Yachty
