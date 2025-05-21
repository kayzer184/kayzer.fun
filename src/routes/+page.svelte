<script lang="ts">
    import foreground from '$lib/assets/foreground.jpg';
</script>

<svelte:head>
  <title>Kayzer's Website</title>
  <style>
    body {
      margin: 0;
      padding: 0;
    }
    section {
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #000;
    }
    .foreground {
      position: absolute;
      width: 100vw;
      object-fit: cover;
      z-index: -1;
    }
  </style>
</svelte:head>

<img class="foreground" src={foreground} alt="Background" />
<section>
    <ul>
      <li>
        <a href="/about">О сайте</a>
      </li>
    </ul>
</section>