# How-To-Install-Vue-Buefy-In-Laravel

Start
	
		You need Vue.js version 2.5+.

Step 1: Install via npm
		
		npm install
		
Step 2: Install buefy
		
		npm install buefy

Step 3: Import and use Buefy in resources/assets/js/app.js

		import Vue from 'vue';
		import Buefy from 'buefy';
		import 'buefy/lib/buefy.css';

		Vue.use(Buefy);

		OR

		Vue.component(Buefy.Checkbox.name, Buefy.Checkbox);
		Vue.component(Buefy.Table.name, Buefy.Table);
		Vue.component(Buefy.Switch.name, Buefy.Switch);

Step 4: Include Material Design Icons

		<link rel="stylesheet" href="//cdn.materialdesignicons.com/2.0.46/css/materialdesignicons.min.css">
		
If you want to customize the icons or the theme, refer to the customization section on the documentation.

Alternatively, you can use a CDN or even download

		<!-- Buefy CSS -->
		<link rel="stylesheet" href="https://unpkg.com/buefy/lib/buefy.min.css">

		<!-- Buefy JavaScript -->
		<script src="https://unpkg.com/buefy"></script>
		// Global variable
		Vue.use(Buefy.default)
