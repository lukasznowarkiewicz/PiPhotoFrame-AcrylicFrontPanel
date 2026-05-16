# PiPhotoFrame-AcrylicFrontPanel  
  
### Motivation  
  
I was curious to see how well LCSC’s acrylic panel design service works, so I decided to create a front panel for a Raspberry Pi Zero photo frame. It should have a shiny surface, a few buttons, an LED backlight, and a cutout for the LCD screen.  
  
### Design  
  
An initial design idea was requested from ChatGPT, and after a few prompts, a satisfactory result was achieved.  
  
![Image](Attachments/6F22DBB2-4772-4848-B0BF-418772CB25E9.png)  
  
Then asked for vectorized version:  
  
![vectorized_panel.svg](Attachments/B2101563-471B-4231-8C96-D44C6F729D97.svg)  
  
And made some manual corrections:  
  
![Screenshot 2026-04-08 at 23.43.40.png](Attachments/944571CF-B318-4A21-9A6D-191EA2E0C663.png)  
  
  
For creating mechanical drawings, I used KiCad as CAD software. I converted SVG to DXF using an online tool and imported it into KiCad. I renamed layers to reflect their functions in panel design: panel edges, glue, translucent, and parts. There is no structured way for doing this; it was just my approach to make that information clear.   
  
![Screenshot 2026-04-09 at 09.13.52.png](Attachments/9ED25F41-DB67-4C00-B798-6D1E182256AD.png)  
  
Submitted order on LCSC:  
  
![Screenshot 2026-04-09 at 09.28.51.png](Attachments/FD52E347-DAD0-41F2-9D82-DB6AF7FE9D41.png)  
  
  
  
### Received panels  
  
Panels came out very good. Keep dimensions, everything as expected, cutout, buttons outlook.   
  
![Image](Attachments/85348DB0-76E9-479D-8DC9-D6DD0AE357DD.jpeg)  
  
![Image](Attachments/9C2A6354-3827-4634-9164-1B0DF67B8EBF.jpeg)  
  
### Assembled photo frame  
  
Assembled the frame with the LCD screen, Raspberry Pi, and buttons backlight. I personally like how it came out. It looks pretty good, especially in the dark.   
  
![Image](Attachments/8F9D3D01-C2CC-4F88-B7FD-BF70AF2F1285.jpeg)  
  
  
![Image](Attachments/C0DEC925-A465-4D4D-A78B-C48779001975.jpeg)  
  
  
  
  
  
