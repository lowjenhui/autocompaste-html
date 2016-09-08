The new IV is: "Number of articles displayed"

I created a JSON generator to output the JSON for the blocks and trials.
The JSON is then copied into a JSON file.

To vary the number of articles displayed and set it to the ones I choose,
I modified interface.js and ACPToolkit.js

interface.js now takes in a new parameter, article_to_show
var iface = new AutoComPaste.Interface(wm, engine, data_file, article_to_show);

My experiment is hosted on github pages at:
lowjenhui.github.io/autocompaste-html

I have also created a practice trial for the users to practice using the given JSON files.

There is also a break screen which correctly sets the start time of the next trial when 
participants resume the experiment after a break.

Main experiment only:
	Ctrl-C has been disabled when participants the trial technique is ACP.
	Check is made for blank answers. 


Thank you!
Julia :)



== References ==
I would like to acknowledge and thank these people/soucres for their help in this assignment.
 
 - Leong Wei Ming (Answering all my really stupid questions)
 - Charmaine Ong (Suggesting a JSON generator for all the articles that needed to be created)