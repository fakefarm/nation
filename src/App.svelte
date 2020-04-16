<script>
	export let name;
</script>

<main>
	<h1>{name}</h1>
	
  <div class="glitchButton" style="position:absolute;top:20px;right:20px;"></div>
  <p>What is a nation but a collection of laws, lands, and love of the people, places, and things which it contains.</p>
</main>

<style>



	main {
    font-family: 'Inconsolata', monospace;
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>