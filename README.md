# Make your own Word Reader toy!
Here you will find a tutorial and all needed ressources to construct a DIY Word reader toy from scratch!
This work is still in progress. As of now (Jan 31st, 2022) there's not much in there. I've barely scratched the surface and there's much prototyping to do, let alone productizing.

## Intro

Most kids have a phase where, just after learning the alphabet, they will spend hours on end asking what `[RANDOM LETTER COMBINATION]` sounds like.

This is actually pretty fun to do with your kid! But as a complementary tool to help them learn how to read faster, here is a toy that cuts the middle man (that is, you) and tell the word that your kid has created out of random letters, automatically.

## Give me more details about this toy!


## But how does it work actually?

This toy is composed of four parts:

1. word bank and sound generation, composed of a DF Player Pro and a Speaker, with a word dataset and a jupyter notebook to produce the word bank
2. letter recognition, composed of 8 proximity + color sensor, 8 white LEDs and an I2C multiplexer
3. an orchestration piece composed of an Arduino microcontroller and an action button
4. the actual letters, composed of knock-off Scrabble letters and colored stickers



## Complete step-by-step building instructions


---

# WIP

### Next steps

1. Test DFPlayer Pro with speaker
2. Test file playing and whether we can try/catch unknown files
3. Test push-button logic with hardware debounce
4. Solder logic level board
5. Order 1 white led, build small cardboard structure for proximity level and color sensors
6. Test Proximity level, find good interrupt threshold
7. Test color sensor, test color stickers, develop color proximity algorithm
8. Build on top of color proximity algorithm for letter identification
9. Flesh out word-to-speaker code
10. Order another color/proximity sensors
11. Solder and test I2C multiplexer
12. Order other color/proximity sensors + white leds + logic level converter if needed
13. Build complete prototype on breadboard
14. Add battery to prototype and test prototype without USB connection
15. Design box
16. PCB Routing with Raph
17. Order PCB, optionally order parts and solder everything (if not included in PCB)
18. Build box, including PCB
19. ...
20. Profit :)


