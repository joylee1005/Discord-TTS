<img src="icon.png?raw=true" width="75" align="left">

# [Discord Text to Speech Bot](https://discordapp.com/oauth2/authorize?client_id=801286916082237441&scope=bot)
Text to speech Discord bot using [Vocodes](https://vo.codes).

Massive thanks to [NamesJoeyWheeler](https://github.com/NamesJoeyWheeler) for adding so many new voices!

[15.ai](https://15.ai) voices have been removed upon request by the author.

## Commands
### Join
`tts_join`

*Joins the voice channel you are currently in.*

### Leave
`tts_leave`

*Leaves the voice channel.*

### Say
*The following commands make the characters say anything you want.*

*If the bot is in a voice channel, the speech will play through this channel.*

*If not, the speech will be sent as an attachment.*

#### [Voices](https://vo.codes)

Alan Rickman - `tts_rickman`

Anderson Cooper - `tts_cooper`

Arnold Schwarzenegger - `tts_arnold`

Barack Obama - `tts_obama`

Bart Simpson - `tts_bart`

Ben Shapiro - `tts_shapiro`

Ben Stein - `tts_stein`

Betty White - `tts_white`

Bill Clinton - `tts_bill`

Bill Gates - `tts_gates`

Bill Nye - `tts_nye`

Bob Barker - `tts_barker`

Boomstick - `tts_broomstick`

Bryan Cranston - `tts_cranston`

Christopher Lee - `tts_lee`

Craig Ferguson - `tts_ferguson`

Crypt Keeper - `tts_keeper`

Danny DeVito - `tts_devito`

Darth Vader - `tts_darth`

David Cross - `tts_cross`

Donald Trump - `tts_trump`

Dr. Phil McGraw - `tts_phil`

George Takei - `tts_takei`

George W Bush - `tts_bush`

Gilbert Gottfried - `tts_gottfried`

Hillary Clinton - `tts_hillary`

Homer Simpson - `tts_homer`

J. K. Simmons - `tts_simmons`

James Earl Jones - `tts_jones`

Jim Cramer - `tts_cramer`

Jimmy Carter - `tts_carter`

John Oliver - `tts_oliver`

Judi Dench - `tts_dench`

Larry King - `tts_king`

Leonard Nimoy - `tts_nimoy`

Lisa Simpson - `tts_lisa`

Mark Zuckerberg - `tts_zuckerberg`

Michael Rosen - `tts_rosen`

Mitch Mcconnell - `tts_mcconnell`

Moistcr1tikal - `tts_penguinz0`

Mr. Fred Rogers - `tts_rogers`

Mr. Krabs - `tts_krabs`

Neil deGrasse Tyson - `tts_degrasse`

Palmer Luckey - `tts_luckey`

Paul Graham - `tts_graham`

Paula Deen - `tts_deen`

Peter Thiel - `tts_thiel`

Richard Ayoade - `tts_ayoade`

Richard Nixon - `tts_nixon`

Ronald Reagan - `tts_reagan`

Sam Altman - `tts_altman`

Sarah Palin - `tts_palin`

Saruman - `tts_saruman`

Scout - `tts_scout`

Severus Snape - `tts_snape`

Shohreh Aghdashloo - `tts_shohreh`

Sir David Attenborough - `tts_attenborough`

Solid Snake - `tts_snake`

Sonic - `tts_sonic`

SpongeBob SquarePants - `tts_spongebob`

Squidward - `tts_squidward`

The Boss - `tts_boss`

Tommy Wiseau - `tts_wiseau`

Trevor Philips - `tts_trevor`

Tucker Carlson - `tts_tucker`

Tupac Shakur - `tts_tupac`

Vegeta - `tts_vegeta`

Wilford Brimley - `tts_brimley`

Wizard - `tts_wizard`

Yami Yugi - `tts_yugi`

## Setup
1. [Create your app with a Bot](https://discordapp.com/developers/applications/me).
2. Copy your bot's secret token and [paste it on this line](ttsbot.js#L8).
3. Go to `https://discordapp.com/oauth2/authorize?client_id=<CLIENT_ID>&scope=bot`, with `<CLIENT_ID>` as your app's client ID.
4. [Install Node.js](https://nodejs.org/en/download): `brew install node`
5. [Install FFmpeg](https://www.ffmpeg.org/download.html): `brew install ffmpeg`
6. [Install the dependencies](package.json#L37-L40): `npm install`
7. [Run the bot](ttsbot.js): `npm start`
