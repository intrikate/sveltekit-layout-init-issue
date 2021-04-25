<script>
	import {onMount, onDestroy} from "svelte";

	console.log("Layout init"); //
	onMount(() => console.log("Layout mount"));
	onDestroy(() => console.log("Layout unmount"));
</script>

<a href="/">Home</a> <a href="/other">Other</a>

<slot />
