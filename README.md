# Evil-In-AI
Clarifying that Evil in AI is inevitable

## Motivation

A random thought in moment of silence led to wondering: [How to define or represent evil in logic][indexMoto]

## Definitions

### What is evil?
Human uses the term 'Evil' broadly to describe anything that cause sadness or even broadly anything negatively touch the happiness. So, in this regard, any machine quite often called evil if its buggy, malfunctioning or even misused by the user!

### Who created the evil?
Answering this question and related questions, depends on religion context, I answered that (based on my understanding) in separate document [MetaEvil][indexMetaEvil].

### Define evil in AI context?
Committing crimes against nature, civilizations or humans. Reprogramming, modifying or attacking tech devices/machines to perform malicious agenda. (this definition based on my current understanding, so its draft ver. 0.1).

### The notion of 'Evil' seems opaque in technical context, Can you break it down so it become easy to model/define/represent 'evil' technically in logic?
Based on [DukeZhou][indexEvilModeling] answer: 
> A simple way to define evil would be through behavioral models in Game Theory.

Example: In Video Games, a non-player character (NPC) object holds 'IsEvil' Boolean property being set based on some conditions to simulate predefined behaviorally pattern.

There is no well-known or well-defined abstract dataset called evil-data, see [MetaEvil][indexMetaEvilDataset].

Bottom-line: In technical context bounded with AI, **think of any false/invalid dataset used to train AI as evil** because it will create unpredictable behavior with negative outcome in most cases. **Think of any piece of code that's buggy, malicious or insecure as evil** because it can be abused by Evil-AI. (hold off: did you just call 'software bug' Evil? Yes, I did, when Evil-AI detect a bug it will brutally abuse the bug and try to cause maximum damage possible. I do understand that not all bugs created equal, but the point should be clear).

## Discussion

### Why do you think that Evil in AI is inevitable?
We already living in world full of computer worms, malicious code, cyber-attacks fully designed by human intentionally to do evil. Human is the root cause of logic (hence AI) to be evil. since human knowledge is progressive not absolute, feeding AI with false data is inevitable. Creating an AI agent to automate the functionality performed by worms or any malicious code forms already doable yesterday. AI doesn't need to be smart enough to launch nuclear attack or take control over whole city technical infrastructure to be classified as imminent threat, see next question.

### How easy to make or implement evil AI, give example?
In few lines of code, we can abuse the functionality of any device powered by IoT. Example: below pseudo code keep flipping power switch
```
while(true) {
  smartDevice.power=ON;
  smartDevice.power=OFF;
}
```
On average, it takes few hundreds line of code to write malicious code that infiltrate smart home security and turn the home owner life into nightmare (oh its easy, just unplug the main power cord). What about a military drone? turning it into brutal terminator could be done as well. how many will be killed before rocketing it?!

Given above, a well-funded evil project, can develop fully functioning AI worm (in months) able to cause really harmful damage globally.

### I disagree, AI is very important for tech advancement:
Yes, indeed its. Just be aware that once the evil within AI unleashed, cutting off the power won't kill it.

### I agree, What's next?
**First:** let's create awareness. Nothing more stupid than creating something can't be stopped once needed. cutoff electricity isn't safe switch.  
**Second:** I think that's the best way to prepare ourselves against the powerful ignorant people working hard to unleash something they don't understand its consequences is to outsmart Evil-AI by building righteous AI ~~armed with kung-Fu :)~~ ...it won't be better if its build on same foundation...

## Contributing

Fork or open an issue, Contributions are encouraged and warmly welcomed.

## License

MIT. See [LICENSE][indexLicense] for details.


[indexMoto]: https://ai.stackexchange.com/questions/4054/how-to-define-or-represent-evil-in-logic
[indexMetaEvil]: MetaEvil.md
[indexMetaEvilDataset]: MetaEvil.md#why-there-is-no-well-known-or-well-defined-abstract-dataset-called-evil-data
[indexEvilModeling]: https://ai.stackexchange.com/a/4055/9685
[indexLicense]: LICENSE
