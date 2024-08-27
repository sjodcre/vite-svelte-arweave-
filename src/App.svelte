<script>
  import {router, Route} from 'tinro'
  let count = 0
  router.mode.hash()
</script>

<Route path="/">
  <h1>Permaweb Counter</h1>
  <div>Count: {count}</div>
  <div>
    <button on:click={() => count++}>Inc </button>
  </div>
  <hr/>
  <a href="/about">About</a>
</Route>

<Route path="/about">
  <h1>About Permaweb Counter</h1>
  <a href="/">Go Home</a>
</Route>

<!-- https://arweave.net/QcWY3ApiZz7RFzcTSnDTUrVQHBdnzSKtRuqu0a-ikzI -->