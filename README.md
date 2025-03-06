# Ollama Cog Model - qwq:32b

This is an implementation of the Ollama model [qwq:32b](https://ollama.com/library/qwq:32b) as a [Cog](https://github.com/replicate/cog) model.

## Development

Follow the [model pushing guide](https://replicate.com/docs/guides/push-a-model) to push your own model to [Replicate](https://replicate.com).
    
## Basic Usage

To run a prediction:

    cog predict -i prompt="How many r's are in the word: strawberry"


## Output

    Let's see. The word is "strawberry." I need to find out how many 'r's are in it. Okay, first, I'll look at the word: s-t-r-a-w-b-e-r-r-y. So, I'll go through it letter by letter.

    Starting with the first letter: s, not an 'r'. Next, t, not an 'r'. Then r, that's one 'r'. Okay, count is one so far. Next letter is a, not an 'r'. Then w, not an 'r'. Next is b, no. Then e, no. Next is r again, so that's two 'r's now. And then another r, so that makes three 'r's. Finally, y, not an 'r'.

    So, total 'r's in "strawberry" are three.

    Wait a minute, let me double-check. Sometimes I might miss a letter. Let's look again: s-t-r-a-w-b-e-r-r-y.

    s: no

    t: no

    r: one

    a: no

    w: no

    b: no

    e: no

    r: two

    r: three

    y: no

    Yes, definitely three 'r's.

    I think that's correct.