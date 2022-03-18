<template>
  <div class="about">
    <!-- <h3>EGOR & VANYA PIZDEZCCCCCCC HULuGANbI</h3> -->
    <button class="hello">
      <h3>Muse</h3>
      <p>Compliance</p>
    </button>
    <button class="hello">
      <h3>Muse</h3>
      <p>Compliance</p>
    </button>
    <button class="hello">
      <h3>Muse</h3>
      <p>Compliance</p>
    </button>
    <button class="hello">
      <h3>Muse</h3>
      <p>Compliance</p>
    </button>
  </div>
</template>

<style lang="less">
.about {
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  justify-items: center;
  grid-auto-rows: 200px;
  grid-gap: 50px 20px;
}

button.hello {
  background-color: transparent;
  border: 1px solid var(--vt-c-text-dark-2);
  border-radius: 20px;;
  width: 200px;
  height: 200px;
  display: flex;
  flex-flow: column;
  align-items: center;
  &:hover {
    background-color: rgba(255, 255, 255, 0.1);
  }
  h3, p {
    color: aliceblue;
    // color: var(--vt-c-text-dark-2);
  }
  h3 {
    font-weight: 600;
    margin-top: 30px;
  }
  p {
    margin-top: 40px;
  }
}
</style>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
  }
}
</style>