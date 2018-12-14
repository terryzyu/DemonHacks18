# DemonHacks 2018 #
DemonHacks is a hackathon hosted at DePaul University. Students from Chicagoland university are welcome to participate in this hackathon.

Our entry is a Twitter tweet analysis program utilizing Tensorflow to determine if replies/reactions to the tweet were positive or negative. The program also generates a word cloud visual to help see the frequency of certain words.

Using the Twitter API via Tweepy, we're able to pull the contents of a Tweet. From there we can recursively gather all replies and feed them into the text classifier. From there it determines the reactions and generates a word cloud.
