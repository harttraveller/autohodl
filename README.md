# autohodl

A command line tool that allows you to do recurring buys of algorand on coinbase pro and transfer them to your algorand wallet, thus avoiding the fees that coinbase shakes you down for on their normal consumer platform, while maintaining a set-and-forget system, that optimally makes it less of a psychological strain to hodl.

**Benefits**
- Automatically transfer to your algorand wallet so you can set and forget
- Minimize coinbase fees while staying entirely within their terms of service

**Cons**
- May be mildly confusing for non-programmers. I've done my best to ameliorate that problem in the set up tutorial though.

### Note

Bugs: I threw this together in an afternoon, I would be unsurprised if there are some bugs here and there. If you get any, please submit an issue and I will do my best to fix it promptly!

Disclaimer: I'm a 21 year old cog sci student/data scientist, not a cryptocurrency/security expert, use at your own risk!



A command line tool you can 

Raspberry pi

How to set up

Coinbase API does not seem to allow you to transfer directly from your bank account to coinbase pro using their API, however you can bypass this and still minimize fees by setting up a recurring buy of USDC on their main platform, and then periodically transferring the USDC that accumulates in your normal coinbase account to your coinbase account.



Security features
- AES 256 encryption of keys stored locally
