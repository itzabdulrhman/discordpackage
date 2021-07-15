<script>
    import { link } from 'svelte-routing';
</script>

<template>
	<footer>
        <p>An open source app.</p>
	</footer>
</template>

<style>
    footer {
        grid-row-start: 2;
        grid-row-end: 3;
        background-color: var(--third-background-color);
        padding-top: 1rem;
        padding-bottom: 1rem;
        margin-top: 2rem;
    }

    footer p {
        margin: 0;
        margin-left: 1rem;
    }
</style>
