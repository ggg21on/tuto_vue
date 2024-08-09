<template>
  <div id="layout">
    <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/">Events</RouterLink> |
          <RouterLink to="/about">About</RouterLink>
        </nav>
      </div>
    </header>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped>
#layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

nav {
  text-align: center;
}

main {
  flex: 1;
  padding: 1rem;
}
</style>
