# hw1

Make the bubbles tiny or huge

line 10 radius: random(50, 100)//        change the number in the bracket,could change the bubbles' size
               radius: random(0, 100)//    change the bubbles' radius from 0 to 100 and appear randomly in the program 
              
Make the bubbles' motions more vigorous

line32 bubble.x += random(-1, 1);//    
line33 bubble.y += random(-1, 1);//   

line32 bubble.x += random(-5, 5);//      change all 4 numbers’ absolute value in the bracket become bigger at the same time
line33 bubble.y += random(-5, 5);//      when the absolute value become bigger and bigger, bubbles' motions become more and                                            more vigorous

Change the bubbles' colors

line26 fill(230, 200, 200, 200); //        change the first 3 numbers in the bracket could change the color when you click the                                           bubbles and change the 4th number could change the bubbles' transparency when you                                             click the bubbles 

line 28 fill(230, 220, 200, 200); //      change the first 3 numbers in the bracket could change the initial color and change the 4th                                           number could change the bubbles' transparency 

Change the initial number of bubbles

line6 for (var i = 0; i < 100; i++)//      change the number i<10, if the number become bigger the initial numver of bubbles                                              will become more

Any other changes you find interesting 

line22 if (dist(mouseX, mouseY, bubble.x, bubble.y)< bubble.radius)//     if change the "<" to ">", the color of the bubbles      will revise from the initial color to the color when you click
