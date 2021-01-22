<script>
  import Profile from "./Profile.svelte";
  import Stories from "./Stories.svelte";
  import Footer from "./Footer.svelte";

  export let nickname;
  export let name;
</script>

<div class="Sidebar">
  <div class="Sidebar-container">
    <Profile nickname="jcdelrioe" name="Juan Carlos Del Rio" />
    <Stories />
    <Footer />
  </div>
</div>

<style>
  .Sidebar {
    position: relative;
    padding: 4.5em 0 0 0;
  }
  .Sidebar-container {
    position: fixed;
  }
</style>
