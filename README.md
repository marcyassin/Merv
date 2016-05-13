# Management for Emergency Response Volunteers

##Django Apps: 
Tasks, Recommender, API, merv

### Tasks: 
handles task creation, storage, updating, and deleting

Models 
 * Task
   * id : Task ID
   * collaborative : team collaboration skills necessary
   * language : foreign language experience needed
   * outdoor : task environment - indoor vs outdoor
   * transportation : transportation resources required
   * task_name : name of the task
   * task_description : description of task
   * timestamp : datetime of task creation
   * updated : datetime of last task update
 * Scores
 

And here's some code! :+1:

```javascript
$(function(){
  $('div').html('I am a div.');
});
```

This is [on GitHub](https://github.com/jbt/markdown-editor) so let me know if I've b0rked it somewhere.


Props to Mr. Doob and his [code editor](http://mrdoob.com/projects/code-editor/), from which
the inspiration to this, and some handy implementation hints, came.

### Stuff used to make this:

 * [markdown-it](https://github.com/markdown-it/markdown-it) for Markdown parsing
 * [CodeMirror](http://codemirror.net/) for the awesome syntax-highlighted editor
 * [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) for syntax highlighting in output code blocks
 * [js-deflate](https://github.com/dankogai/js-deflate) for gzipping of data to make it fit in URLs
