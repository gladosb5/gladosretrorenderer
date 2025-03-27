# 2012-gladosretrorenderer
it is a renderer made by h4606 skidded by gladosb5 yes yes use this client for the BEST experience of YOUR life.
https://archive.org/details/roblox-studio_20250323  

## how 2 compilered?
ok so so skidders here you go:
download or use git clone lolol then
open the sln thing and also like right click on the rbxrenderhook yaya adn u have to like
open confiration manager and like set release to debug and x64 to x32 becuz roblox no no like x64..
then like u open the studpe or if your lazy just use extreme injector... i DONT care.
so in studpe you go to drag the robloxstudio.exe yaya and u have to yaya like yay and yay and like you have to
go to functions, like right click on the LEFT side in the EMPOTY space and like u need to like click on new impoort that whatever then
you uhh need to like select your dll "rbxrenderhook" and yeah. thats it ok yeah and also if it asys missing dll oH NO!!! then u need to
download theseee dlls yeah

## Functions  
`render(filepath, x, y, url)`  
Example:  
`render("TestRender.png", 1280, 720, "http://www.roblox.com")`  

The URL is where the image gets sent. If you don't want to send it, use a **random valid URL** instead.  
  
## Troubleshooting
1. Help! It's crashing!  
  - Make sure you compiled in **DEBUG** mode and that you're using **OPENGL**

2. I have no sky in my renders!
  - Make sure you are using **OPENGL**. **Direct3D** often makes the sky invisible.  
  
## FAQ
1. Can you hide the sky?
  - **Yes! You can.** Just change from OpenGL to Direct3D in studio settings, and also change **ViewBase::CreateView** to **Direct3D9** instead of **OpenGL**  
  
2. Why release this?  
   - I believe that a lot of revivals would benefit from this a lot, and I don't think that this should be gatekept.  
