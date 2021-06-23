# binarybot-public
Collection of Binary.com bots from the web. These are mostly bots found while experimenting and playing with binary.com. I would not recommend any of them, especially anything with a Martingale.

This is more about a bit of fun, playing with the markets with a "scratch like" interface.

# CAPITAL AT SERIOUS RISK!!!!
Please don't use these bots in anything but virtual account. Binary.com is regulated by the gambling authority it calls itself a broker but it's a Bookie with an API.

## Remember these rules:
- If it has a straight up Martingale it's not profitable in the long run
- If someone says you shouldn't be "greedy" and only run a bot for a short period, it means its not profitable and will wipe your profits.
- "proof of success" is not a profit over the first 10,20,100 runs but over 1000s.

## Types of trades
There are many trade options the most common you find are:

- Digits, This covers anything where you are making a prediction on the last digit of a tick. This is straight up guessing a random number there is no magic solution, over a 1000 runs each bot will average about the same. Normally Digit bots are "differs" so where you bet the next number is not x they return a very low amount. Things to watch out for... Bot's with Martingale at this level have a Martingale at 11x normally which will wipe most pots in 3 consecutive losses.
- Rise/Fall, What I would call the more traditional binary options you are placing a bet the market will have risen or fallen after the alloted time. You don't have to say by how much simply gone up, gone down. While still gambling markets have trends and especially over a longer period (minutes not seconds/ticks) there is some predictability. Also the returns are much higher then digits, allowing some money management strategies. Bot's that can follow a trend can do well. *Note Rise/Fall is availabe on non binary.com controlled indicies such as forex, for some accounts*
- Higher/Lower, are simple rise/fall but where you indicate the value will be above or below a given barrier based on where it started. This provides a bit more flexibility compared to Rise/Fall. For example you can set the barrier slightly below the current value, but predict it will go higher, giving you a safety net at the cost of reduced profit. Alternatively you can raise the barrier for much larger returns.

There are plenty of other options, and the other folder has a range of different types of trading bots.

## How to run these bots?
You can run these bots on https://bot.binary.com simply download the raw xml file, or clone this repo and then when logged in, click the "folder icon" to load.

Make sure before you run, your bot you are in your demo refered to as virtual account (starts with VRTC)



