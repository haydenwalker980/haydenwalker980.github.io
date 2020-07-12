# Making a Heroku Discord Bot

Like many, you probably want to become a Discord bot creator. Like NotSoSuper and Carl#0001. I get it.
But, it takes major PC knowledge. Sad.

And you've probably heard of BotGhost. Sounds amazing...until you look deeper.

To remove BotGhost branding, you'll need to **pay up.** Not anymore.

The GitHub and Heroku communities have been creating AMAZING Discord bot templates. Modmail, moderation, heck, even literally **DESTROYING ANOTHER SERVER.**

I'll teach you how to start.

First, make your application at the [Discord Developer Portal](https://discord.com/developers/applications).

Next, navigate to your **Bot** section and copy your bot token.

Meanwhile, fire up Heroku, create an account, then use [this beginner template](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FScarletKuro%2FNadekoBot-Heroku-Auto-Deploy&template=https%3A%2F%2Fgithub.com%2FScarletKuro%2FNadekoBot-Heroku-Auto-Deploy).

In `SELFBOT_TOKEN`, paste the token we generated.

In `SELFBOT_CLIENTID`, paste your Client ID (aka your bot's User ID, or Application ID).

In `SELFBOT_OWNEDIDS`, paste your User ID (not just Username#1234). You can include multiple owners in this fasion: `OWNERID1,OWNERID2,OWNERID3`. Obtain your User ID by enabling Developer Mode in Settings > Appearance, then right-clicking on yourself and then clicking "Copy ID". Same goes for other users.

That's all. You don't have to touch another thing but the "Deploy App" button, just let your bot build and...

**Voila! You have a working Discord bot.**

The default prefix for this template is `.`, but you can change this using `.defprefix newprefix` and replace `newprefix` with your new prefix.

Read some tips [here](https://haydenwalker980.github.io/tutorials/making-a-heroku-discord-bot/tips)!
