<script>
	import Page2 from './+page2.svelte';
	let question = 'What is Svelte?';
	let src = 'image';
</script>

<h1>{question}</h1>
<h1>{question.toUpperCase()}</h1>
<p>
	Svelte is a tool for building web applications. Like other user interface frameworks, it allows
	you to build your app declaratively out of components that combine markup, styles and behaviours.
	These components are compiled into small, efficient JavaScript modules that eliminate overhead
	traditionally associated with UI frameworks.
</p>

<img {src} alt="A {src} dances." />

<p>This is a paragraph.</p>

<Page2 />

<style>
	p {
		color: brown;
		font-family: Arial, Helvetica, sans-serif;
		font-size: 2em;
	}
</style>
