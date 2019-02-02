# CSS Bounce

<a href="https://gyazo.com/f4d7471c668f90252af70a221589ffb2"><img src="https://i.gyazo.com/f4d7471c668f90252af70a221589ffb2.gif" alt="Image from Gyazo" width="288"/></a>


# Hover animation

<a href="https://gyazo.com/627816aa6760f7326ab8177890216b83"><img src="https://i.gyazo.com/627816aa6760f7326ab8177890216b83.gif" alt="Image from Gyazo" width="294"/></a>

**You can use my animation in your website using this css:**

```
/*// BOY //*/

.boy{
    position: absolute;
    top: 130px;
    left: 20px;
    transition: transform 200ms ease-in-out;
}

.text_boy{
    position: absolute;
    top: -29px;
    left: 46px;
    font-family: Courier bold;
    font-size: 90%;
    opacity: 0;
    transition: opacity 50ms 1000ms ease-out;
    pointer-events: none;

}

.bubble_boy{
    position: absolute;
    top: -20px;
    left: 40px;
    opacity: 0;
    transition: opacity 100ms 500ms ease-out;
    pointer-events: none;
}

.boy:hover{
    transform: scale(1.1);
}

.boy:hover .bubble_boy{
    opacity: 1;
}

.boy:hover .text_boy{
    opacity: 1;
}
```
# :rocket: Rocket animation (http://raketti.pigg.fi/).

<a href="https://gyazo.com/6aa14f89836123bc7cb89b919fd433b5"><img src="https://i.gyazo.com/6aa14f89836123bc7cb89b919fd433b5.gif" alt="Image from Gyazo" width="800"/></a>

**Javascript and css. Each star you see is its own div and their position is changed by using css animations**
