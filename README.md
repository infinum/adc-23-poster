# Audio Unit debugging and reverse engineering

A poster presented at ADC 2023.

## Resources

For more details about AUSampler and our work on it:

- [Exploring AUSampler](https://infinum.com/blog/getting-started-with-au-sampler/)
- [Can AUSampler survive dynamic chain changes](https://infinum.com/blog/au-sampler-dynamic-chain-changes/)
- [AUSampler missing documentation](https://infinum.com/blog/ausampler-missing-documentation/)

And associated source code for it can be found [here](https://github.com/infinum/mysterious-sampler).

[Facebook's Fishhook](https://github.com/facebook/fishhook)
[Hopper Disassembler](https://www.hopperapp.com/)

For relevant bug reports we filed with Apple:

- [AVAudioUnitSampler ignoring new notes when an unknown limit is reached](http://openradar.appspot.com/radar?id=5598760801402880)
- [Publicly expose hidden AUSampler parameters and properties](http://openradar.appspot.com/radar?id=5621421787054080)
- [RefillBuffer crash when sending a lot of notes to sampler](http://openradar.appspot.com/radar?id=5619393195147264)
- [Tech note incorrectly states Sampler search paths](http://openradar.appspot.com/radar?id=5575719308492800)
- [AVAudioUnitSampler's preset cleaned up when chain is reconnected](http://openradar.appspot.com/radar?id=5514004654981120)
- [Resonance connection not working on iOS](http://openradar.appspot.com/radar?id=5551119480651776)

## Poster PDF

You can find a poster [here](au-debugging-reverse-engineering.pdf).
