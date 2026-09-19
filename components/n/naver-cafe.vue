<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="poo40skbv"/><path class="jod9mpw5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naver-cafe" /></template>
<style>
.jod9mpw5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.752 20.543a5.045 5.045 0 0 1 0 10.09h-.5M30.723 9.294a8.597 8.597 0 0 1-8.597 8.597h-5.972a8.597 8.597 0 0 1 8.597-8.597z");
}

.poo40skbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.752 27.245c0 6.45-5.229 11.68-11.679 11.68s-11.679-5.23-11.679-11.68v-6.702h23.358z");
}

</style>
