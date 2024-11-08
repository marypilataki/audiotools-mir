# audiotools-mir

Object-oriented handling of audio signals, with fast augmentation routines, batching, padding, and more.
The repo is a fork of [AudioTools](https://github.com/descriptinc/audiotools) with additional features for MIR tasks (work in progress).

In the current version of the repo, we have added the following features:
- Generate labels for multi-pitch estimation tasks from MIDI files.
- Generate noisy labels for multi-pitch estimation tasks using predictions from the pretrained [Basic Pitch model](https://github.com/spotify/basic-pitch).
