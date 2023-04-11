## What is AI an Machine Learning?

**Artificial intelligence** (AI) is a type of computer technology that helps machines perform tasks that typically require human-like intelligence. This can include things like recognizing speech, identifying objects in images and learning from data. Rather than giving machines human-like qualities, AI involves developing algorithms and systems that can process information and do things on their own, without needing humans to give step-by-step instructions.

You’ve probably done a bit of coding before, so you know programs are usually written: they are **rules-based**. Programs are a series of instructions and rules that the computer must follow exactly. `If this, then that.` 

Machine learning doesn’t work that way - it’s **data-driven**. Instead of using lots and lots of rules to cover every possibility, machine learning takes large amounts of data about a particular topic to build an ML model. The ML model is a representation of something. Usually the representation is of the real world, but it can also be of an imaginary context.

<p style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
</span><h3>Example: Spotify Recommendations</h3></span>

All the songs on Spotify have been put into a big database, where each song not only has data about the artist, title and album, but also about how the song sounds. Each song has been analysed and has data attached to it for values like:

<span style="color: #0faeb0">Danceability:</span> describes how suitable a track is for dancing! A value of 0.0 is least danceable and 1.0 is most danceable.

<span style="color: #0faeb0">Instrumentalness:</span> predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks like podcasts are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no talking at all.

<span style="color: #0faeb0">Speechiness:</span> detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the speechiness value. 

Every time you listen to music on the service, the app takes note of how often you listen to each song and (if you rate music you listen to) how much you like it. Once the application has a certain amount of data about your choices, the model compares that data to all the songs in the database and predicts things that are similar to your tastes that you will probably also like.

</p>

