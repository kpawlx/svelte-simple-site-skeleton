<script>
    import '$lib/styles/style.css';
</script>

<header>
	<a href="/">Home</a>
	<nav>
		<ul>
			<li><a href="/blog">Blog</a></li>
			<li><a href="/portfolio">Portfolio</a></li>
			<li><a href="/about">O mnie</a></li>
			<li><a href="/contact">Kontakt</a></li>
		</ul>
	</nav>
</header>

<main>
	<slot />
</main>

<footer>&copy; 2023 kpawlx</footer>
