<script lang="ts">
	import Router from 'svelte-spa-router';
	import Home from './components/home/Home.svelte';
	import Navigation from './components/Navigation.svelte';
	import Versions from './components/Versions.svelte';

	// Demo of how to use Routes with svelte-spa-router
	const routes = {
		'/': Home,
		'/versions': Versions,
	};
</script>

<main>
	<!--  Custom Application Titlebar  -->
	<Navigation />
	<Router {routes} />
</main>


<!-- 
*******************************************************************************************
*******************************************************************************************
IF YOU LIKE THIS TEMPLATE AND WOULD LIKE TO SHOW SOME LOVE CONSIDER FOLLOWING ME  *********
ON YOUTUBE AND CHECKING OUT MY OTHER ELECTRON/SVELTE/DENO CONTENT.								*********
*******************************************************************************************
*******************************************************************************************
-->