# Roots
Patches for generative music collaboration in VCV Rack

## Overview
The Roots repository is meant for storing and collaborating on patches that create something new from two different sources of sound/music. 

Originally, the idea came from finding a way to blend between two separate recorded musical sets without mixing directly into eachother. However, the patches can be used freely for any use.

## How it Works

### Inputs
1. Sample A 
1. Sample B
1. Duration of segments
1. Chord for generated middle segment
1. Recording Configuration

### Output
- One .wav file

## How the Repository is Organized
_Roots is composed of branches for varying moods_

### `main` branch: 
- Branch name: `main`
- Where a default patch lives.
- This default patch is the starting point and intended to be used to create new patches from.

### `mood` branches: 
- Branch name: `mood-<name-of-mood>`
  - Eg: `mood-gentle-breeze`
- Similar to software feature branches or environment branching, each `mood` branch is a variation of the `main` branch. 

## Usage
_This repo will assume users are not familiar with Git and will attempt to document with this in mind._

### Requirements 
- [VCV Rack](https://vcvrack.com)
- Modules used in the patch
  - By default, free VCV Rack modules will be in use. 
  - If paid modules are in use, they should be listed and linked to in the patch's README file.

### Setup

#### UI
1. In GitHub's UI, select the branch you want to use (eg: `main` or `mood-gentle-breeze`).
1. Navigate to the `patches` directory.
1. Select the `root-patch` file.
1. Select `Download raw file`.
1. Move the file to your VCV Rack patch directory.
1. Open VCV Rack.
1. Select `File > Open`.
1. Find and select the patch file.
1. **TBD**: will add steps to check for and add missing modules.
1. GG! Happy modulating!



