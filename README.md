<p align="center">
  <a href="https://blobs/pixel.com.ro/">
    <img src="https://blobs/pixel.com.ro/asstes/img/blobs-logo.png" alt="Blobs logo" width="200" height="200">
  </a>
</p>

<h3 align="center">Blobs</h3>

<p align="center">Pure CSS Animated Blobs</p>

## Introduction

Blobs are the smooth, random, jelly-like shapes that have a whimsical quality and are just plain fun. They can be used as illustration elements and background effects on the web.

## Install
Place the downloaded blobs.css or blobs.min.css file to your assets folder, that add a link into the <head> tag.
 ``` 
<link rel="stylesheet" href="assets/css/blobs.min.css">
  ```
  
##  Include via CDN
When you only need to include Blobs compiled CSS, you can use jsDelivr, just add a link into the <head> tag.
  ```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/pixel-s-lab/blobs@main/dist/css/blobs.min.css">
  ```
Settings
Blobs tool is using CSS custom properties (aka CSS variables), so it is super easy to customize them. These settings can be placed as inline style or in separate <style> definition.

| Name |Type | Default | Description  |
| --- | --- | --- | --- |
|  --time| string | 30s  | Time of animation loop in seconds or milliseconds|
| --amount |  int| 2 |  Amount (size) of deformation |
|--fill  |  string|#000  | Fill color of blob|

## Default settings
```
<div class="px-blob">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 747.2 726.7">
    <path d="M539.8 137.6c98.3 69 183.5 124 203 198.4 19.3 74.4-27.1 168.2-93.8 245-66.8 76.8-153.8 136.6-254.2 144.9-100.6 8.2-214.7-35.1-292.7-122.5S-18.1 384.1 7.4 259.8C33 135.6 126.3 19 228.5 2.2c102.1-16.8 213.2 66.3 311.3 135.4z"></path>
  </svg>
</div>
```
 ## Customized settings
Custom settings for --time, --amount and --fill

```
  <div class="px-blob" style="--time: 20s; --amount: 5; --fill: #56cbb9;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 747.2 726.7">
    <path d="M539.8 137.6c98.3 69 183.5 124 203 198.4 19.3 74.4-27.1 168.2-93.8 245-66.8 76.8-153.8 136.6-254.2 144.9-100.6 8.2-214.7-35.1-292.7-122.5S-18.1 384.1 7.4 259.8C33 135.6 126.3 19 228.5 2.2c102.1-16.8 213.2 66.3 311.3 135.4z"></path>
  </svg>
</div>
```
