<p align="center">
  <img src="icon.png" align="center" width="150px" alt="Agrippa logo" />
  <h1 display="inline" align="center"><strong>Rhode</strong></h1>
</p>

Rhode is a LaTeX editor and a companion app for ongoing mathematical research.

It focuses on two aspects:
1. First, it's an intuitive LaTeX editor, with first-class support for RTL languages.
2. Second, it aims at simplifying the process of writing and organizing mathematical content for research, beyond a particular paper or project.

> [!IMPORTANT]
> This project is still in development.

## Installation
Rhode is currently only distributed on Windows (not code signed yet).
To install, download and run the installer from the [latest release page](https://github.com/NitzanHen/rhode-releases/releases/latest).

## Some media

### Start Screen
<img width="1504" height="1004" alt="Rhode Start Screen" src="https://github.com/user-attachments/assets/b77a7bb1-4758-4fff-a4a5-add1654bc30f" />

### Editor
<img alt="Screenshot 2026-09-14 022508" src="https://github.com/user-attachments/assets/df2b768d-9736-46b7-989a-4f37ce4455d7" />
<img alt="Screenshot 2026-09-14 022735" src="https://github.com/user-attachments/assets/e7b3c838-7d79-491f-bbe8-0938354ff658" />

## What's the idea?
The motivation for creating a RTL-focused LaTeX editor is straightforward: most popular editors today (e.g. Overleaf, LyX or VSCode with the LaTeX Workshop extension) have poor support for writing in right-to-left languages.
This is not a simple issue to overcome, since LaTeX syntax is itself written in English, and handling bidirectional text involves handling many subtle points (this is difficult, by the way, not only on the technical level -- with bidirectional text, it's often not even clear what a good solution is supposed to look like). However, a simple, intuitive RTL writing experience can be achieved if care is taken throughout -- and with Rhode I aim to achieve that.

For the second aspect, Rhode aims to assist in the process of continuous mathematical research. 
Think of it as a place to store all the knowledge you need for your research -- that includes papers, books or your notes, but also your own results.
These need not, and are ideally not, restricted to a single paper or project you worked on; rather, I believe there's a benefit to having all the ideas and information, across all areas and projects, put together in one store (in an organized and easy to navigate manner, of course).

There are many popular tools today that offer good solutions ([Obsidian](https://obsidian.md/) is an honorable mention).
However, there are many features that mathematics research could benefit from -- e.g. more granular linking or a flexible, shared preamble -- that are not provided by these apps.

Of course, AI could also be utilized to greatly improve the experience of researching and maintaining the knowledge base. I have plans for that, but it might take some time.

## About this repository
This repo *does not* contains Rhode's source code; it's used to host Rhode's releases and provide documentation (such as the file you're reading right now).
At present, Rhode is not open-source.
