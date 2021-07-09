# My Take-On the Take-On

![The Take On](https://github.com/joemulberry/takeon_the_takeon/blob/main/images/takeon_banner.jpg?raw=true)

### The Introduction  

Some of my favourite moments in football are when a winger receives the ball on the run, goes straight at her defender, with a blur of footwork she leaves the defender for dust. Yet in the data, take-ons are binary boredom - unsuccessful or successful - but we know each take-on is not equal. The public research into take-ons remains embryonic and, largely, unimaginative - which sets the perfect scene for a deeper dive into a action that makes a huge difference in a game.

My research will culminate in a visual dashboard that’s intuitive to consume whilst providing a deeper understanding of a player’s efficiency, objectives and situational tendencies in relation to take-ons. Clubs can be more detailed in their assessment of transfer targets as well as game-preparation to understand the strengths and weaknesses of the opposition’s offensive players.

### The Data

I will use Statsbomb 360 data, self-shilled as the "most comprehensive and contextual event dataset in football". The data includes a 'freeze-frame' for each action which consists of all player positions at the moment in time, with the player and the GKs (if in shot) named. Such rich data provides an exciting oppournity to build event's situational context into models of analysis. I will have access to 190 games of StatsBomb Data AND StatsBomb 360 Data from Spain’s 2020-21 La Liga season, which will consist of all matches for the top 10 teams. 

### The Framework 

The dashboard will be built on top of a new bespoke framework for take-on analysis, whose:

* Close-Quarters Defensive Situational Categorisation 

   Statsbomb 360 data provides us with a freeze-frame of all player positions at the moment of each event. With the take-on location as (0,0), defender locations will be mapped in a 10m diameter around the using KDE and then clustered. The clusterings will be lablled with relevant football language such as 'isolated 1v1' or 'staggered cover' etc. Elements to confirm: 
   * Clustering method? 
   * Orientation, as is? Player -> Centre of Goal?
   * Sidelines and goalines?

* Pre-Action Dynamics 

   This si sth eaisdajn djn aspdjnask dklandknk jnkjn jknknaksdnkjan ansnsnsnakjdkjasdkjnasdnaksjndka nkjkjn asd
   
* Phase of Play 

   Using event data and 360 freeze frame information to assertain the 'phase of play' at the time of a take-on. 
   
   


* Value Gained / Lost 

   Using a 'value' system will be used assign +/- value for each take-on.  
   
   
   
   
   
   
Originality: StatsBomb have the richest event data in the world, and 360 data is the first dataset of it’s kind. We’re looking for innovative approaches to analysing it
Application: Can your work be used to help clubs make better decisions or be the basis for future research?
Feasibility: Is your proposal a realistic one for the given timeframe?
