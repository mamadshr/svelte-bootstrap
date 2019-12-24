<script>
	export let name;
</script>

<div class="container">
	<h1>Hello {name}!</h1>
</div>

<style lang="scss">
	$color: purple;

	@import "../node_modules/bootstrap/scss/bootstrap.scss";

	h1 {
		color: $color;
	}
</style>
