# Synthetic video data generation

This project is designed to generate synthetic abstract video data at a specified level of anomalies.

Anomalies are different types of movements (different direction, size, part of the screen).

This project also allows transition between states to simulate diurnal or weekly cycles in the real world.

## Getting started

Clone the repo to your own system. There is a single Juypter notebook.

## Prerequisites

This program has the following prerequisites:

Python 3.8
Jupyter Notebook 5.0.0 (e.g. via Anaconda)
Pygame - this can be downloaded at pygame.org
libav - can be installed using Homebrew: brew install libav

Note: Homebrew can be installed at command line with: /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

## Operation

To operate this program, use the following steps:

1) Run the entire notebook
2) Wait until enough frames are generated
3) Press a key to interrupt video generation
4) Wait for completion of the video

Warning - disable iCloud synchronisation on the output directory for this program if you produce a large number of frames, otherwise it could tie up your laptop for a long time. 

## Versions

The following changes have been made:

0.1 - Original concept

## Author

Graeme Woods
