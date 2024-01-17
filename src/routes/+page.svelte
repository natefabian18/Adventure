<script lang="ts">
	import ActiveName from '$lib/Name';
</script>

<section class="Main">
	<div>
		Hello {$ActiveName}
	</div>

	<input type="text" bind:value={$ActiveName} />
</section>

<style>
</style>
