<script>
    // Dependencies
    import Router from "svelte-spa-router";

    // Components
    import Header from "./components/header.svelte"

    // Templates
    import Home from "./routes/home.svelte"

    // Routes
    const routes = {
        "/": Home
    }
</script>

<svelte:head>
    <title>
        Document
    </title>
</svelte:head>

<main>
    <Header/>
    <Router {routes}/>
</main>

<style lang="scss">
    :global(*) {
        padding: 0;
        margin: 0;
    }
</style>