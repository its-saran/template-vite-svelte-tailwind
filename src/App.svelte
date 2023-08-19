<script>
    import svelteLogo from "./assets/svelte.svg";
    import tailwindLogo from "./assets/tailwind.svg";
    import viteLogo from "/vite.svg";
    import Counter from "./lib/Counter.svelte";
</script>

<main class="flex flex-col justify-center items-center">
    <p>
        Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
        how to build Svelte apps.
    </p>
    <div class="flex">
        <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
            <img src={viteLogo} class="logo vite h-48 p-6" alt="Vite Logo" />
        </a>
        <a href="https://svelte.dev" target="_blank" rel="noreferrer">
            <img src={svelteLogo} class="logo svelte h-48 p-6" alt="Svelte Logo"/>
        </a>
        <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer" class="flex justify-center">
            <img src={tailwindLogo} class="logo tailwind w-64 p-6" alt="Tailwind Logo"/>
        </a>
    </div>

    <div class="card">
        <Counter/>
    </div>

    <p>
        Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
    </p>

    <p class="read-the-docs">Click on the Vite and Svelte logos to learn more</p>
</main>

<style>
    .logo {
        will-change: filter;
        transition: filter 300ms;
    }
    .logo.vite:hover {
        filter: drop-shadow(0 0 2em #646cffaa);
    }
    .logo.svelte:hover {
        filter: drop-shadow(0 0 2em #ff3e00aa);
    }
    .logo.tailwind:hover {
        filter: drop-shadow(0 0 2em #38bdf8);
    }
    .read-the-docs {
        color: #888;
    }
</style>
