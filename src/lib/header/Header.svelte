<script>
  import { page } from "$app/stores";
  import logo from "./svelte-logo.svg";
</script>

<!-- <header>
  <div class="corner">
    <a href="https://kit.svelte.dev">
      <img src={logo} alt="SvelteKit" />
    </a>
  </div>

  <nav data-sveltekit-prefetch>
    <svg viewBox="0 0 2 3" aria-hidden="true">
      <path d="M0,0 L1,2 C1.5,3 1.5,3 2,3 L2,0 Z" />
    </svg>
    <ul>
      <li class:active={$page.url.pathname === "/"}>
        <a href="/">Home</a>
      </li>
      <li class:active={$page.url.pathname === "/about"}>
        <a href="/about">About</a>
      </li>
      <li class:active={$page.url.pathname === "/todos"}>
        <a href="/todos">Todos</a>
      </li>
    </ul>
    <svg viewBox="0 0 2 3" aria-hidden="true">
      <path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
    </svg>
  </nav>

  <div class="corner">
  </div>
</header> -->

<div class="py-12">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="text-center">
      <a href="/">
        <p
          class="mt-2 text-3xl font-bold leading-8 tracking-tight text-blue-400 sm:text-4xl"
        >
          O.un
        </p>
      </a>
    </div>
  </div>
</div>
