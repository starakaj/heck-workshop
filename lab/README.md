# Lab
With the time we have left, you're of course welcome to do whatever you like. But, if you'd prefer something specific to work on, why not work on this simple lab?

## Concepts
Max is all about mapping. In this workshop, we've seen how to play notes using a regular pulse, how to turn audio into a control signal to trigger sound, and how to apply the envelope of a sound to a live video. The art of mapping has to do with extracting perceptual or performance characteristics of a signal, so that the signal still makes sense when translated to a new domain. For example, when we wanted to use the "loudness" or "feel" of an audio signal to drive a video effect, we took the absolute value of the audio, turning negative values into positive ones. That's because the experience of audio loudness is proportional to the amplitude of the audio signal. Large negative values are just as loud, perceptually, as large negative values. Understanding what works well, when analyzing, combining and remapping signals, is the art of performance interface design. It's also fun.

## Assignment
In this lab, we're going to map mouse and keyboard input to audio signals. Take a look at the patcher called lab-1.maxpat. On top there are two components. One uses the *key* object to detect key presses. The other uses an object called *mousestate* to get the X and Y coordinate of the mouse cursor. Using just these two signals, it's already possible to produce any number of interesting sounds. Your assignment is to use these signals, in conjunction with audio processing objects, to create a performance patch. When you've got a sound you like, try recording it using the Quickrecord feature in the Extas menu.

To see what this might look like, we've provided a number of examples that you can check out. These might not make any sound when you open them up. If that's the case, make sure that audio processing is turned on, and that the gain control in the bottom-left is turned up. Finally, you may need to press space to open up the envelope, "activating" the signal. In lab-1-example1.maxpat, spacebar opens and closes the envelope, while the X coordinate of the mouse controls the oscillator's frequency. Other patchers control the audio signal in more interesting ways.

## Help and Reference
Remember that the help and reference documentation in Max is extensive. You can open the reference by pressing Shift-Command-R, or by finding Reference in the Help menu. The audio processing tutorials, called MSP tutorials, are a great place to learn about how to process audio, and a great starting point for your own audio effects. Remember too that every object has its own help patcher, which you can open by unlocking the patch and then option-clicking on an object, or right clicking on an object and selecting Open Help from the context menu. These help patchers show how to use an object in the context of an actual patch. They are also fully unlockable and editable, so feel free to copy-paste content from these patchers whenever you like.