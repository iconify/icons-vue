<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyeffcixn"/><path class="a2k3lob4a"/><path class="i9o4z6bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sundrug" /></template>
<style>
.a2k3lob4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 5.4c-10.272 0-18.6 8.328-18.6 18.6H8.5v18.6c10.272 0 18.6-8.327 18.6-18.6h12.4z");
}

.fyeffcixn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 24c0-10.272 8.328-18.6 18.6-18.6v4.737");
}

.i9o4z6bah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 24c0 10.272-8.327 18.6-18.6 18.6v-4.737");
}

</style>
