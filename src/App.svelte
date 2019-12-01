<script>
  // Include global variables first
  import "../node_modules/@spectrum-css/vars/dist/spectrum-global.css";

  // Include only the scales your application needs
  import "../node_modules/@spectrum-css/vars/dist/spectrum-medium.css";
  // import "../node_modules/@spectrum-css/vars/dist/spectrum-large.css";

  // Include only the colorstops your application needs
  // import "../node_modules/@spectrum-css/vars/dist/spectrum-lightest.css";
  // import "../node_modules/@spectrum-css/vars/dist/spectrum-light.css";
  import "../node_modules/@spectrum-css/vars/dist/spectrum-dark.css";
  // import "../node_modules/@spectrum-css/vars/dist/spectrum-darkest.css";

  // Include index-vars.css for all components you need
  import "../node_modules/@spectrum-css/page/dist/index-vars.css";
  import "../node_modules/@spectrum-css/typography/dist/index-vars.css";
  import "../node_modules/@spectrum-css/icon/dist/index-vars.css";
  import "../node_modules/@spectrum-css/button/dist/index-vars.css";

  import LoginButton from "./LoginButton.svelte";
  import RepoCard from "./RepoCard.svelte";

  export let name;
</script>

<style>

</style>

<main>
  <h1 class="spectrum-Heading1--display">Select Helix Theme</h1>

  <LoginButton />

  <h2 class="spectrum-Heading2--quiet">Your Repositories</h2>
  <div>
	<RepoCard />
  </div>
</main>
