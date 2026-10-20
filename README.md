# ping_pong
from pygame import *

back = (200, 255, 255)
window = display.set_mode((900, 600))
window.fill(back)
clock = ime.Clock()
FPS = 60

game = True
while game:
    for e in event.get():
        if e.type == QUIT:
            game == False

    display.update()
    clock.tick(FPS)
