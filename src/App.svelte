<script>
    let name = 'World'
</script>

<style lang="scss">
    $color: #ddd;
    :global(body) {
        background: $color;
    }
</style>

<h1>Hello {name}</h1>

<svelte:head>
    <title>Svelte Template</title>
</svelte:head>
