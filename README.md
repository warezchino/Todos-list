# Todos-list
Code based in Mitchell Hudson's work, I saw the videos and is really awesome how is working, unfortunatelly for some reason I only
can see a string of ***** in my console using the inspector code.
Following the YT first video is OK, everything is perfect, the console is displaying the content, but until we start to add
more code especially in this function section:


function listTodos() {
	"use strict";
	for (var i in todos){
	var todo = todos[i];		
		var html = " ";
		var name = todo.name;
		var completed = todo.completed;
		html += "<li>"+name+" "+completed+"</li>";
	}
	$("#list-todos").html(html);
}



after this, is when this code is showing no more stuff in screen... I tried to isolate the problem but my understanding is too limited
by the moment...

Also I'm using brackets editor and somehow is showing me with a lot of warnings, mostly the spaces between the line codes, I wonder if
this is something related to this case.

Anyway, thanks a lot for your  kind help and time Mr. Mitchell

