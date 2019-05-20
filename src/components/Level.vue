<template>
  <div class="app-level-container">
    <div class="container">
    <nav class="level">
      <!-- Left side -->
      <div class="level-left">
        <div class="level-item">
          <router-link to="/" class="app-logo title">
            LOGO
          </router-link>
        </div>
      </div>

      <!-- Right side -->
      <div class="level-right">
        <p class="level-item"><strong>All</strong></p>
        <p class="level-item"><a>Published</a></p>
        <p class="level-item"><a>Drafts</a></p>
        <p class="level-item"><a>Deleted</a></p>
        <p class="level-item"><a class="button is-success">New</a></p>
      </div>
    </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Level'
}
</script>

<style lang="sass">

.app-level-container
  min-height: 5rem
  z-index: 10000
  background-color: #FFFFFF
  box-shadow: 0 3px 3px rgba(0,0,0,0.1)
  .level
    height: 5rem

.app-logo
  cursor: pointer
</style>
