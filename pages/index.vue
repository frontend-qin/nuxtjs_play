<template>
  <div class="container">
    <logo />
    <nuxt-link to="/about" tag="span"
      ><van-button type="primary">默认按钮 </van-button></nuxt-link
    >

    <p>hello world</p>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
export default {
  components: {
    Logo
  }
};
</script>
<style>
p {
  width: 180px;
}
</style>
