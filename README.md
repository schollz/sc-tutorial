# music.hackspace

## installing SuperCollider

<details>
  <summary><strong>### Windows</strong></summary>


## Downloading

[Click here](https://github.com/supercollider/supercollider/releases/download/Version-3.11.2/SuperCollider-3.11.2-Windows-32bit-VS.exe) to download the latest Windows release. This is the *32-bit* release, rather than the 64-bit release, because [the most recent Windows Update prevents the 64-bit version from starting](https://github.com/supercollider/supercollider/issues/4368#issuecomment-832050665). But it will work just fine.

Then [click here](https://github.com/supercollider/sc3-plugins/releases/download/Version-3.11.1/sc3-plugins-3.11.1-Windows-32bit-VS.zip) to download the 32-bit sc3-plugins. Unzip these plugins and then copy and paste the `XX` folder into the following location:

```
XX
```

## Zoom sharing/unsharing

Share your screen, select the SuperCollider window, and then below click on the carrot symbol next to "Share sound" to select "Stereo (High-fidelity)".

![Screen+Shot+2021-06-13+at+10.25.26+AM.png](/uploads/sha256-cf1fbf7435887111d5afca4c3b4a7885dd492d7889f02acf5104ec09c0360736?filename=Screen+Shot+2021-06-13+at+10.25.26+AM.png)

That's it! There shouldn't be any other steps to share your SuperCollider audio over Zoom on Windows.


</details>




## workshop 1 - tone to drone

![img](https://user-images.githubusercontent.com/6550035/118573663-db952100-b737-11eb-9a34-560e38778fcb.jpg)

## workshop 2 - ample samples

![img](https://user-images.githubusercontent.com/6550035/118573658-da63f400-b737-11eb-9308-e3310a184b9b.jpg)


## general

### before we begin

1. open a terminal and ssh into norns. 

copy and paste the following. you only need to do this once.

```
curl https://gist.githubusercontent.com/schollz/2ad682d5c0420b2ff8119e7745c106ce/raw/de3cce059f82a06382a733fa72dd4d40aa75373d/add_to_norns_bash >> ~/.bashrc
```

2. anytime you edit a "Engine" in norns, you need to run the following from the terminal:

```
restartn
```

that will restart crone, and recompile all your engines.

<details>
  <summary><strong>How do I share audio in Zoom?</strong></summary>

make sure you have Zoom v5.5+

to share audio you can do "Share screen" and click the screen you want to share. then at the bottom click "Share sound" and click the menu next to it to change it from "Mono" to "Stereo (High-fidelisty)".

![zoom](https://user-images.githubusercontent.com/6550035/118572448-50b32700-b735-11eb-94c3-3de4d7776f10.jpg)
</details>


