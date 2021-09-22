<template>
  <div id="app" class="container">
    <p>
      <font-awesome-icon icon="trash" />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure soluta
      cumque voluptatum consequuntur nisi officia optio, error fugit quia vero
      facilis dignissimos accusamus autem distinctio voluptate laboriosam unde,
      illum reiciendis.
    </p>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
export default {
  name: "App",
  components: {
    FontAwesomeIcon,
  },
};
</script>

<style lang="scss">
@import "node_modules/bootstrap/scss/bootstrap.scss";
</style>
