<script>
	import '../app.css';
</script>

<main class="relative flex min-h-screen flex-col items-center justify-center">
  <a
    href="https://vercel.com/templates/next.js/blob-sveltekit"
    class="group mt-20 sm:mt-0 rounded-full flex space-x-1 bg-white/30 shadow-sm ring-1 ring-gray-900/5 text-gray-600 text-sm font-medium px-10 py-2 hover:shadow-lg active:shadow-sm transition-all"
  >
    Deploy your own to Vercel
  </a>
  
  <slot />
  
  <div
    class="flex justify-center gap-1 font-light text-gray-600 w-full max-w-lg text-center mt-6"
    >
    <a
      href="https://vercel.com/blob"
      class="font-medium underline underline-offset-4 hover:text-black transition-colors"
    >
      Vercel Blob
    </a>{' '}
    demo.
    <span>Built with</span>
    <a
      href="https://kit.svelte.dev/"
      class="flex items-center font-medium underline underline-offset-4 hover:text-black transition-colors"
    >
      <img src="svelte_logo.png" alt="svelte logo" class="h-6 mx-1" />
      <p>SvelteKit</p>
    </a>
    .
  </div>
  <div class="sm:absolute sm:bottom-0 w-full px-20 py-10 flex justify-between">
    <a href="https://vercel.com">
      <img src="/vercel.svg" alt="Vercel Logo" width={100} height={24} />
    </a>
    <a
      href="https://github.com/vercel/examples/tree/main/storage/blob-sveltekit"
      class="flex items-center space-x-2"
    >
      <img src="/github.svg" alt="GitHub Logo" width={24} height={24} />
      <p class="font-light">Source</p>
    </a>
  </div>
</main>