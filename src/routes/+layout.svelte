<script>
	import '../app.css';
	
	let { children } = $props();
</script>

<!-- Discrete yellow banner for closure notice -->
<div class="bg-yellow-100 border-l-4 border-yellow-500 text-yellow-700 px-4 py-3 text-sm text-center">
	<p class="font-medium">
		📅 Le cabinet est fermé du 7 au 16 juillet inclus.
		<span class="font-normal">Merci de votre compréhension.</span>
	</p>
</div>

<div class="text-[#11181f] overflow-x-hidden">
	{@render children()}
</div>
