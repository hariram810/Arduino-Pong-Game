# Arduino-Pong-Game

![Screenshot (719)](https://user-images.githubusercontent.com/118633170/209281219-093f3ca0-9994-4d17-9e2b-a403ec659a90.png)

If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA



PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA



3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users


OLED stands for Organic Light Emitting Diode. The OLED displays are very small and have high resolution. These displays have no back light and they makes their own light. That’s why these are very low power devices.

![Screenshot (720)](https://user-images.githubusercontent.com/118633170/209281242-104d4da3-1a9e-48cb-9e28-6b544f67fbf3.png)
![Screenshot (721)](https://user-images.githubusercontent.com/118633170/209281258-6e36fe1c-76a8-4b7b-8940-e296ba694430.png)


Working
When the voltage is applied to the OLED. The current flows from the cathode to anode through the organic layers of the OLED. The cathode gives the electrons to the emissive layer of organic molecules and the anode removes electrons from the conductive layer of organic molecules.

At the boundary between the conductive and emissive layer, electron holes are created. These holes are filled by the electrons and the OLED emits light. The color of the OLED depends upon the organic molecules used.

I have figured out a way to develop the popular pong game on the Arduino board.

The game is not complicated but interesting to develop and play.

Here 0.96 inch OLED display and two buttons have been used. The display is small but enough for our project. Two buttons will be used to move our racket up and down.

The display size is 128x64 pixels. The first and last 16 pixels will be used to display scores.

The scores will be displayed vertically.

![Screenshot (722)](https://user-images.githubusercontent.com/118633170/209281281-f9a64501-7f68-490b-b40c-fd5e014082b0.png)


One racket will be controlled by the player, and the second one, the opponent will be controlled by the Arduino. We will write code so that it will try to move towards the ball. At the beginning of the game, it will move slowly, and then, it will gradually accelerate.

We will control the ball direction through ball_direction_X and ball_direction_Y variables. The ball will move in a specified direction each moment. If the ball hits a wall, ball_direction_Y will be reversed and the same logic for ball_direction_X and rackets.


As you noticed above, the newRound function takes as input winner (player/enemy). The input is required to increase the appropriate score. In the function, we will reset all the required game-related variables, print updated scores, display all game objects, and if required update the speed of the enemy and ball. The game will become more difficult as you progress through it.

The OLED that we are going to use has individual 128X64 white OLED pixels. It is 0.96’’ (25mm X 14mm) in size. The OLED’s of other sizes are also available. The OLED used in this tutorial is monochrome (Only one color) but you can also get the OLED’s having several colors.

This OLED uses the SPI communication to communicate with Arduino. The SPI communication is faster than the I2C communication so this will make our display faster.

![Screenshot (723)](https://user-images.githubusercontent.com/118633170/209281306-98dc3937-d37b-4aac-a893-53ba38a99f8e.png)


It is notable for the fact that, with a short time, the game is full of events and actions, it is not primitive and not arcade. I can't remember any other game (including the modern one) that could be compared to it. Usually, either the gameplay is noticeably simpler, or the game time is noticeably longer.

It seemed to me that a game in the style of "Star Patrol" could be implemented on its basis. If not "mega", then "Due" should have been enough!



A breadboard. This is a plastic board with metal leads underneath. It allows you to connect wires without soldering. Each column of the breadboard is a single lead. If you want to connect two wires, stick them into the same column.

Breadboards are a temporary arrangement. So, should you decide to make this game permanent, you’ll need to solder some components together. But for now, a breadboard will be good enough.

The data is printed on the OLED in the form of picture loops. The firstPage() shows the start of the picture loop. Next to it, we need to create the “do while” loop. Anything we want to show on the OLED should be written inside “do while” loop. The “do while” loop will keep on running until the nextpage() returns a ‘1’.

The u8g.setFont(u8g_font_helvB10) command will set the font. This library has different font sizes and design which you can find from the below link.

U8glib fonts

The development was carried out in free time from work, but then the process was accelerated by the fact that I was at home in quarantine for some time due to the pandemic.


![Screenshot (725)](https://user-images.githubusercontent.com/118633170/209281357-7f7808bb-6a76-4132-bc9a-a2181a35107f.png)

I put together a mockup from what was at hand and started developing an advanced version.

The u8g.drawStr(30, 10, “Welcome “) command will print the “welcome” at the X, Y position. The value ‘30’ is for the horizontal position(X) and the value ‘10’ is for the vertical position(Y). The other draw commands are also working like that.

The u8g.setPrintPos(75, 15) command used in the code will set the pointer to X (75), Y (15) position. Then you can print the sensor output there by using the u8g.print() command.

At the center of the board, there’s a chip that you can program in any way you like. To program it, you attach the Arduino to your computer and run special software that puts your code onto the chip.

See those black sockets on both sides of the board? That’s where you attach wires to carry electricity. The chip that you programmed can read the values of that electricity and act on them.

Using Arduino: a quick example

![Screenshot (724)](https://user-images.githubusercontent.com/118633170/209281338-192c517c-82a8-4c24-87fa-8dd79e8d0e99.png)

Before I go into Snake, here’s a simple home project you can do with Arduino to make sense of how the system works.

On one side, you connect the Arduino to two wires that lead to a humidity sensor. The sensor will output a voltage between 0.1 volt and 5 volts, corresponding to how humid the air is. Let’s say the main wire from the sensor is connected to Socket 1 on the Arduino.

On the other side of the Arduino, connect an LED light that can be either on or off. To fire it up, you need to send it 5 volts of current. Let’s say the LED is connected to Socket 2.
