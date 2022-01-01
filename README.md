# custom-race-ac-12_6_21

This repo contains most of the work that I have done in an attempt to get worgen and goblins as available playable races in World of Warcraft 3.3.5a on AzerothCore. The last point at which this work was functional (Not complete) was August of 2021. Since then, AC has seen many updates that have resulted in my server install being unable to build properly and currently I don't care to work on getting it working.

The models used for this project were taken from this repo:
https://github.com/mthsena/trinitycore_scripts

The Icons for the racial abilities were pulled from WoWHead, resized, and converted to BLP using this program:
https://www.wowinterface.com/downloads/info18810-Blpc.html

Patching work was done using mpq-editor and WDBX Editor, and what work I did on the racial abilities was done using Stoneharry's spell editor.


As of the last time I worked on the project, some racials were done and the two races were in a playable state quite similar to Cata, however they had some issues. Goblins had the primary issue of missing their racials because I believe those would have to have core edits to properly work, or at least some. Worgen were missing Two Forms as I couldn't figure out how to get that working properly using Demon Form as a base. Primary issue I felt with worgen was an issue where their model would change whenever they shapeshifted as a druid. The links below are examples of what the models changed to upon returning from shapeshift form. I never found any leads with regards to this issue, though it could be an issue with the models themselves.


Base: https://media.discordapp.net/attachments/520029389136855069/881044283342340148/unknown.png?width=460&height=640

Dire Bear: https://media.discordapp.net/attachments/520029389136855069/881044351457853480/unknown.png?width=499&height=640

Moonkin: https://media.discordapp.net/attachments/520029389136855069/881044473281396766/unknown.png?width=478&height=640

Cat: https://media.discordapp.net/attachments/520029389136855069/881044574120849478/unknown.png?width=432&height=640

Travel: https://media.discordapp.net/attachments/520029389136855069/881044646975930368/unknown.png?width=503&height=640

Tree of Life: https://media.discordapp.net/attachments/520029389136855069/881044714600677376/unknown.png?width=499&height=640

Aquatic: https://media.discordapp.net/attachments/520029389136855069/881044886990757918/unknown.png?width=479&height=640

Swift Flight: https://media.discordapp.net/attachments/520029389136855069/881044971090747472/unknown.png?width=528&height=640


Both races I believe had their skeleton (The model that their corpse is replaced by upon resurrecting) use the stand-in blue-white grid box as well and were missing most if not all emotes and voice lines. I felt that the level stats could be taken from Mists of Pandaria without issue since I didn't have a Cata server on hand and the human warrior I compared between MoP and WotLK were the same.

The DBC files included are likely a mix of what was provided by AzerothCore (I believe an enGB client if it makes a difference) and my own enUS client, with plenty of meshing of the two if that could cause any confusion.

Recent work on this project is now being released here: https://github.com/benjymansy123/mod-worgoblin
