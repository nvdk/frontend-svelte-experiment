<div class="au-c-app"  {...$$restProps}>
 <slot />
</div>

<style>
.au-c-app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  overflow: auto;
  background-color: var(--au-white);

  @include mq(medium) {
    overflow: hidden;
  }
}
</style>