# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/mumzkid/MY_PROJECT_MAZE.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://imgur.com/a/iJGB9eG)

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)]

=================================
BEHIND THE SCENE
=================================

Given a short time to do alot, I had spent the 1st week reading the given material on ray-casting and the use of SDL2. A lot of the concepts were a bit sketchy because I hadn’t visited my Intranet due to my busy schedule. Working with React and NodeJs were a bit challenging as well.

CHALLENGES
The major challenge of the 1st week had been getting used to NodeJs and React. My approach was to reach out to some of my peers whom I trust were great at programming, and I also got access to other peers who did the same project was ideal.


PROGRESS
Most of the coding has been done on the project to try and meet the MVP, however, a -Werror flag error is still a big issue to clear. Hopefully, in the coming few days, the error will be dealt with. I would rate the progress as a 7 out of 10. The challenges are as mentioned above and hugely I have been on target in terms of completion goals. The general functionality of the app/challenge has not been met and that can be considered as the incomplete section.

CHALLENGES

TECHNICAL
Installing npm and NodeJs was highly tasking as I had errors due to the fact that my NodeJs version would not support npm in my sandbox. I had to install this NodeJs app on my computer before configuring my Visual Studio Code to it. I overcame this issue by querying Google. After the installations and the codes, it was hard to push them to my Github Repo. I spent a couple of hours on the phone with Michael Oni who guided me patiently all through the process. Unfortunately, throughout the whole episode, I forgot to take snapshots. I experienced commit errors, refs as well as gitignore problem files and at a point I doubted my code skills and was ready to give up but we pulled through!

NON-TECHNICAL
The first in this category would be my mental health next to electricity issues as well as my PC’s weak battery. It is the dawn of a new era in my country and we do have a fuel crisis as well as a prolonged lack of electricity. My mental health was in chaos as I couldn’t help but ponder on how long we would be in this situation as the cost of living skyrocketed as well, in just a few weeks! Whew! Sometimes during my sessions, I get headaches and eye pain but this will be remedied soon as I hope to incorporate Blu-ray glasses in my already medicated lenses.
So that's it! I hope to give you an update once more when the project is up and running! Till then, See you!

Love,
Akintayo A.
