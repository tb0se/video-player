# YouTube Video Player

A custom clone of the Youtube video player.

## Getting started

### Yarn

Install yarn globally.

```sh
npm i -g yarn
```

### Installation

To get a local copy follow these simple steps.

1. Clone the repo

   ```sh
   git clone
   ```

2. Install the required dependencies

   ```sh
   yarn
   ```

3. Run the application

   ```sh
   yarn dev
   ```

## Create Preview images

```sh
ffmpeg -i assets/Video.mp4 -vf fps=1/10,scale=120:-1 assets/previewImgs/preview%d.jpg
```
