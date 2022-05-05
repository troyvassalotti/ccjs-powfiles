---
title: A PNG is Worth and Entire Website
date: 2022-05-04
tags: ["ccjs"]
---

# Websites

They're great! They come in all shapes, sizes, and colors.

# The Downsides

- Complicated tooling
- Servers
- Portability

# Next Generation Website Packaging: **POW**

> POW stands for Packaged Offline/online Webpage. It turns out the png format includes ways to save metadata alongside the image file. A powfile has a metadata entry that contains a zip file that contains a full website.

# POW Files

An entire website packaged in a single PNG image that you can carry around in your pocket.

# Why Though?

- It's a niche market
- It's quirky
- It's makes you feel like a spy

# Getting Started

- [powfile-cli](https://github.com/troyvassalotti/powfile-cli)
- [powplayer](https://powplayer.netlify.app)
  - [GitHub](https://github.com/troyvassalotti/pow-player)

# Step 1: A Website

Create your website in a directory of your choosing. This is the directory where `powfile` will enter and zip into a PNG image.

# Step 2: Zip It

While in the `powfile-cli` root, run:

```shell
# replace "input-image.png" with the name of the PNG you want to POW
# replace "input-directory" with the name of the directory containing your HTML to embed
# replace output.png with your desired output name

node cli create -i path/to/input-image.png -o path/to/output.png path/to/input-directory
```

# Step 3: powplayer

Go to [powplayer](https://powplayer.netlify.app) and upload your generated image.

# Step 4: Advanced

You can create a powfile with multiple pages!

# Lessons Learned

A valuable experience in working with and debugging someone else's repository from years ago.
