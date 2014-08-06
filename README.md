Recoil
======

Recoil uses `gulp`, `browserify`, `livereload` and `less` to build complex web applications into deployable versions. It's goal is to minimize [Dev-Prod Parity](http://12factor.net/dev-prod-parity), so the developer is always running the "prod" version of the web app because it rebuilds everytime a file changes. It does this while still being incredibly fast, sub-second in most cases. 

It leverages technogolies like `livereload` to instantly refresh the developer's webpage whenever there are changes. 

		Built in source mapping
		Componenet based architecture, grouping the code, styling and assets of componenet together, rather then seperating them by type.
* Leveraging node modules
* Compatible with [Bower]()


Archteciture.json
==================

In Recoil, javascript is the source of truth, you only need to include a componenet within javascript, and Recoil will make sure both it's styling and assets are included within the project. It does this by creating an `architecture.json` file which stores the dependacy structure of your application. 


Feedback
=========

Recoil will try it's best to let you know when your code is wonky, and to gracefully keep building once it's fixed. It will also selectively build


Project Structure
==================



How To Use
==========

Include `recoil` in your gulpfile.js in your project. Configure it



Options
=======

	{
		dev_paths : Array
		debug : Boolean
		build_path : String
		template_path : String
		complete_tasks : String
		cdn_paths : Object
		
		ignore_exts : Array
	}

