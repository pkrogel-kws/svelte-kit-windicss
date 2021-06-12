<script lang="ts">
	import 'virtual:windi.css';
	import Header from '$lib/Header/index.svelte';
	import '../app.css';

</script>

<Header />

<main flex="~ 1 col" w="full" max-w="1024px" m="x-auto y-0" p="4" box="border">
	<slot />
</main>

<footer flex="~ col" justify="center" items="center" p="4 sm:(y-8 x-0)" font="bold">
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>
