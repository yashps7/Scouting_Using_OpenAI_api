# Football Alchemist AI
### Transforming raw football data into golden scouting reports through AI alchemy.
Football Scouting using OpenAI API call and getting data from [FBref](https://fbref.com/en/) and [Fotmob](https://www.fotmob.com/).

It will scrape data from Fotmob and FBref. Initially FBref data was enough but now due to some complications we first scrape player data from FBref using Google Colab and save it into [table.md](https://github.com/yashps7/Football_Alchemist_AI/blob/main/table.md). Then we use web scraping and scrape data from Fotmob. 
 We use scraped data and input into our prompt and pass prompt to our Scouting assistant i.e. openAI api model. Ofc you have to use your own openAI key.
 As we can see we get Detailed Scouting report of player, Statistics and also Player Trait Radar.
 Using this data we can have basic overview of player and take steps upon informed decision.

 ### Some Demo Outputs

 ##### Recently I've added few more features, below images are old one but still 70-80% similar.
 
 1. Lamine Yamal
    
    16 year old crazy talent and hope for the Barca future.
    
    ![Output Image](https://github.com/yashps7/Football_Alchemist_AI/blob/main/output/lamine.png)

    His Trait Radar
    
    ![Trait Image](https://github.com/yashps7/Football_Alchemist_AI/blob/main/output/lyTraits.png)

2. Phil Foden

   Man city's wonderkid who's now became a man in absence of his fellow star teammate Kevin De Bruyne.

   ![Phil](https://github.com/yashps7/Football_Alchemist_AI/blob/main/output/foden.png)

3. Alexia Putellas

   Two time Ballon D'or winner showing off her talent time and time again.

   ![Alexia](https://github.com/yashps7/Football_Alchemist_AI/blob/main/output/alexia.png)

## Future Scope
Just few factors and we can see how data can influence scouting. Ofc there is scope. We can incorporate data like player contract, market value, team shortcomings and other values to gain even more insights and conclusions. Incorporating is underway. For contributions you can contact me.
