## Chapter 2: 307 Temporary Redirect
Sam chuckles at the absurdity of it all and decides to play along by making a request to the first goblin, Squeak.

"I only have a few Jira tickets left in the sprint anyway, so... what harm is there in seeing what happens?", she thought.  This had to be a harmless prank, anyway.

She thought it might've been Jerry, the senior architect from one of the backend teams who left a few years ago.  He was the kind of guy who always smirked when you asked him a question, because he always believed he knew the answer whether he actually knew what he was talking about or not.  Jerry also had a terrible sense of humor.  No one laughed at Jerry's jokes back then, and she wasn't sure if she was laughing, or just confused now, either.  Maybe both at the same time.  Who makes jokes with an endpoint these days outside of the Joke API?

"This has to be Jerry..." she rationalized further as she Google'd for lists of prime numbers.  She then found a binary number converter online, and that was it: she had a list of twenty prime numbers.  That seemed like a reasonable way to start.  She sent the POST request back to Grumble like so:

```
{
  "goblins": [
    {
      "name": "Grumble",
      "answer": "1, 10, 11, 101, 111, 1011, 1101, 10001, 10011, 10111, 11101, 11111, 100101, 101001, 101011, 101111, 110101, 111011, 111101, 1000011."
    }
  ]
}
```
...and then, she waited.

She waited almost a full minute.  She thought the request was about to time out, but then, she received...

```
{
  "goblins": [
    {
      "name": "Grumble",
      "response": "You have potential.  Let's see what else you find."
    }
  ]
}
```

Was this a backhanded compliment?  It's hard to tell through text, but Sam knew she would need to delve deeper if there was a possible answer to what was going on here.


### What does Sam decide to do next?
- If Sam decides to dig deeper into the codebase for further research, turn to [Chapter 4](Chapter4.md).
- If Sam thinks this is all a ruse and seeks out Jerry to find out the truth, turn to [Chapter 5](Chapter5.md).