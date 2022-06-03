<div class="nav">
  <a href="/">
    <img src="logo.png" alt="Modmail logo" />
    <h2>Modmail</h2>
  </a>
  <div class="grow" />
  <div class="nav-links">
    <a class="nav-link" href="/docs">Docs</a>
    <a class="nav-link" href="https://github.com/modmail-io">GitHub</a>
  </div>
</div>

<style lang="scss">
  $height: 2.5rem;

  .nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    height: $height;
    background-color: lighten($col-bg, 4%);

    padding: 0 0.5rem;

    a,
    .nav-links {
      display: flex;
      flex-direction: row;
      align-items: center;
      text-decoration: none;
      color: $col-text;

      img {
        height: calc($height - ($height / 7));
        margin-right: 0.5rem;
      }
    }

    .nav-link {
      height: $height;
      padding: 0 1rem;

      &:hover {
        background-color: lighten($col-bg, 8%);
      }

      &:active {
        background-color: lighten($col-bg, 12%);
      }
    }
  }

  @media (min-width: 768px) {
    .nav {
      padding: 0 20%;
    }
  }
</style>
