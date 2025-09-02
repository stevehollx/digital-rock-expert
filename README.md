# digital-rock-expert

## Details

Use a list of songs and spotify URLs to play a song guessing game digitally. This is inspired by the board game Hitster, but uses a different song list (US Rock Billboard charts) and plays 100% digitally without any cards, so it offers a complete novel experience from what they sell as a physical board game.

I use this to play with family, groups, and parties where we guess rock songs, since paid commercial versions of this game are focused on pop music.

You can choose how deep into the billboard charts you want to go for each year. There is a bit of a selection bias towards later years if you go over 20 hits per year, since there are only 20 hits recorded each
year in 1950 - 1956, and 40 until 1965. 1966 - present has 100 records per year.

Because this is mainly played as a group game at a couch or table, code is shared via a python notebook. I like to run the notebook in pythonista on my ipad and mirror the screen to a TV so everyone can see the score. Then whoever is pared to a stereo scans the QR codes and plays the spotify URLs. The scanning person can still scan and flip their phone over and particiapte as part of a team without seeing what is playing.

## Installation
1. Copy rock_expert_digital.ipynb to [Google Colab](https://colab.research.google.com), or to local folder that can run Jupyter notebooks
2. Copy content/rock-chart-final.csv to the content/ folder that you run the notebook from (i.e. upload the file to Google Colab's files section for the notebook. This is a temp folder that Google will clear aer runtime expire).
3. Run the notebook.
4. Pair a smartphone to your audio destination. This phone will scan the spotfy URL QR codes to play music. Ideally you subscribe to Spotify, otherwise you can play a 30s clip for free.
5. Play!

## Other

Check out my [getbillboardhits(https://github.com/stevehollx/billboard-hits) repo if you want to pull down other billboard charts. The code is a bit messy since I really only needed to pull this down once and you can grab my resulting song file instead, but this capability may be useful if you want hits from another genr or country chart, or want to try and replace spotify with another streming service for the URLs.
