<script>
  import HookDetail from '../../components/HookDetail.svelte';

  export let data;
  export let request;
</script>

<style>
  a {
    margin-bottom: 1rem;
    display: inline-block;
  }
</style>

<svelte:head>
  <title>{data.hook.hook} Hook Interface: Elder.js Example Project</title>
</svelte:head>

<a href="/">&LeftArrow; Home</a>

<HookDetail {...data} />

<img
  src="https://elderguide.com/images/elderjs-hooks-v100.png"
  alt="Elder.js hook Lifecycle"
  style="max-width:100%; margin:1rem 0;" />
