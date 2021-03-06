<div align="center">
    <br>
    <p><img src="https://img.kirameki.one/2v01x5KE.png" height="300" alt="Kirameki"></p>
    <a href="https://discord.gg/kKPZdA6"><img src="https://discordapp.com/api/guilds/464440032577716238/embed.png" alt="Discord Server"/></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0.html"><img src="https://img.shields.io/badge/license-AGPL%20v3-FF9175.svg"></a>
    <a href="https://abal.moe/Eris/"><img src="https://img.shields.io/badge/library-Eris-FF9175.svg"></a>
    <a href="https://github.com/riyacchi/chariot.js"><img src="https://img.shields.io/badge/framework-Chariot.js-FF9185.svg"></a>
    <img src="https://img.shields.io/badge/database-MariaDB-FF9185.svg">
    <img src="https://img.shields.io/badge/node-10.15.3-FF9185.svg">
</div>

# About
Kirameki is an extremely powerful Discord & Twitch bot tailored to the needs of gaming communities, especially [osu!.](https://osu.ppy.sh) Kirameki comes with extremely useful and powerful functionality like several popular game data profile lookups, tight Twitch TMI & osu! Bancho chat integrations, translations, community bonding, auto moderation and a lot more.

# Usage
This repository is ***not*** meant for self hosting purposes, as Kirameki heavily relies on other internal services which aren't part of this repository. As a result there is no support on getting Kirameki up and running for self hosting. Please bear in mind ***the license*** Kirameki ships with if parts of the code hosted here on GitHub were to be reused for personal projects.

# Contributions
Contributing to Kirameki is welcome if you think a certain feature or command is missing and needs to be added. Please bear in mind to only issue a pull request on the master branch and stick to the code style of Kirameki. Helper functions that could be reused anytime down the road **must** be put into the KiramekiHelper class. A command template can be found in the constants folder of this repository ([or click here](https://github.com/riyacchi/kirameki/blob/master/src/constants/Template.kirameki)). Unnecessary command properties e.g. `nsfw` or `owner` can simply be deleted. The `execute` method of each command class is the "main" method if you so will, which means that the main command logic should be put inside of there. Available parameters include `message` and `kirCore` where `message` is the message object emitted from Eris and `kirCore` the main bot instance including all attached properties e.g. the database `kirCore.DB` and the osu! module `kirCore.osu`. If you have more questions just read the code of already finished commands or join the Kirameki guild and leave us a message.

# Community
The Kirameki community is delighted about any single one of its valuable community members. Come [join us on Discord](https://discord.gg/kKPZdA6) and have a chat with us!

# License
Kirameki is released under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html) license.

This software makes use of the Discord API library **Eris** provided by [abalabahaha](https://github.com/abalabahaha/eris), which is licensed under the [MIT License.](https://opensource.org/licenses/MIT)

