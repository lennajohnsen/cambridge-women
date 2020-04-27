# cambridge-women
Crowd Sourced City class project spring 2020


# text editors
I use Visual Studio Code myself, https://code.visualstudio.com/ but there are other options

# github desktop
So I use Github Desktop to keep track of changes. https://help.github.com/en/desktop/getting-started-with-github-desktop

You'll first want to CLONE this repo, and when you've done changes COMMIT them and then PUSH to the repo. 

Try to only make changes to the respective html/css pairs to avoid complications (for the map I've created map.html and map.css and games has games.html and cards.css) -- the css files can all go into one file technically, but this is likely easier to learn. styles.css has global formatting like text size.

Add any images into the "assets" folder, and if you do end up writing a script (either python or js, I think both will work) then put it in the Scripts folder.

# tutorials
I'd suggest doing codeacademy for HTML and CSS tutorials-- honestly like most coding things, there's loads of forums.

For card flipping, here is a tutorial: https://www.w3schools.com/howto/howto_css_flip_card.asp just with CSS (this is why I made a cards.css file)


# how to run
to run this locally on your machine, go to the Terminal option along the top bar (between Run and Help) and select New Terminal then type

npm install

into your terminal.

Once that has installed, type

http-server

then navigate to 

http://127.0.0.1:8080/

to see the site. use ctrl-shift-r for a hard refresh if it looks like things aren't updating.

Use ctrl-c to stop the server from running. 
