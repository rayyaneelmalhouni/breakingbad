<script>
	
</script>

<main>
	<div class="container">
		<h1 class="title">Breaking Bad</h1>
		<h3 class="sub-title">A TV Series</h3>
		<div class="selector-machine">
			<select name="" id="">
				<option value="Apple">Apple</option>
				<option value="Apple">Apple</option>
				<option value="Apple">Apple</option>
			</select>
			<button class="button-searcher">Search</button>
		</div>
		<div class="informations">
			<div class="text">
				<h3>Name</h3>
				<h3>NickName</h3>
				<h3>Ocuupation</h3>
			</div>
			
			<img src="" alt="character-img" class="character-image">

		</div>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: 'Poppins', sans-serif;
	}
	
	.container {
		width: 80%;
		max-width: 1200px;
		padding: 10px;
		border: 1px solid #333;
		margin: 0 auto;
		border-radius: 15px;
		text-align: center;
	}
	h1, h3 {
		
		font-size: 1em;
	}
	.container .title {
		color: #333;
		font-size: 2em;
	}
	.sub-title {
		color: blue;
		margin-bottom: 1em;
	}
	.text {
		margin: 1em 0;
	}
	.selector-machine {
		width: 80%;
		margin: 0 auto;
		display: flex;
		justify-content: center;
	}
	.selector-machine select {
		width: 60%;
		border-radius: 10px;
		padding: 5px;
	}
	.selector-machine button {
		border: none;
		border-radius: 10px;
		background-color: blue;
		color: white;
		padding: 2px 3px;
	}
	.selector-machine button:hover {
		background-color: rgb(48, 48, 253);
	}
	
</style>