<script>
	const mountForm = () => {
		Cognito.mount('68', '#form');
	};
</script>

<svelte:head>
	<script
		defer
		async
		src="https://www.cognitoforms.com/f/seamless.js"
		data-key="VIFwyLJpI0-1pUDbhQ8wSg"
		data-form="68"
		on:load={mountForm}></script>
</svelte:head>

<div>
	<h1>This is the survey page</h1>
	<div id="form" />
</div>
