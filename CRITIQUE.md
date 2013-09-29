## September 28, 2013

When people tweet or share photos on Instagram at a Studio-X event, they often use a hashtag to connect their tweet to the event. Your project provides a sort of environmental or architectural tag that can be applied to the event itself, as well as any tweets, Instagram photos or other information that is related to the event. This is a new kind of tag, say, an `arch tag`, rather than a `hash tag`.

You will use this tagging system to produce a new online user interface for Studio-X content based on sorting by this information. You will build out a database that pulls in this environmental information - from sensors in the space that will measure temperature, humidity, pressure, the number of people in the room, etc, and from other sources (like servers that give the cycle of the moon, or the number of sun spots that day) - and coorelates it to Studio-X information (such as: events from the GSAPP events [calendar](events.gsapp.org), tweets, Instagram photos, flickr sets, etc).

This requires you designing and building 3 things:

1.	You will build a single physical unit with a Raspberry Pi and an Arduino installed in Studio-X NYC that will collect a minumum of 7 pieces of information (temperature, humidity, barometric pressure, light levels, number of people in the space, etc - all up to you to decide) and send them to the cloud where they will be logged and timestamped in a database.

2.	You will build a web site that will allow the user to sort Studio-X events by the strange traits that you will collect. For instance, they will be able to sort by all events that occurred in a room with a temperature above 85º F.

3.	You will build a database hosted in the cloud that will collect this environmental data and also pull in Studio-X events from the GSAPP events calendar, and tweets, Instagram photos and anything else that is related to Studio-X, and you will correlate it all together in this database. This database will serve your website in #2 above. Later, you can also try to pull in data from online sources that will allow you to include other random information like the number of sun spots on the day of the event, astrology information, horoscope, top news stories, etc.



## September 20, 2013

When we meet on Monday or Tuesday you should know which content platform you want to use. I suggest you stick with something well known like Tumblr, Twitter and Instagram. Be sure to look on https://npmjs.org/ and search for the platform you choose to make sure there is a Node.js module to connect to it's API.

Each content platform has it's own flavor, a specific content format (square image for Instagram, 140 characters for Twitter...), an audience, a frequency, a tone and even a geographic dominance. You should have a reason for choosing the content platform that keeps this in mind and exploits it. You may also want to choose a platform that is not America specific, such as Weibo, which has Node modules https://npmjs.org/search?q=weibo. 

Your task is to explain to us what kind of content is getting produced, how it's getting produced, where it's going (Tumblr, youtube, Google+, Weibo...), at what frequency, and VERY IMPORTANTLY who might want to consume your content and why.
