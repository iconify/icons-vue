<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uu5j-vbau"/><path class="y5xj3-y4k"/><path class="gubza_b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muzei-source" /></template>
<style>
.gubza_b4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.67 32a5.91 5.91 0 1 0 9.26-5.14");
}

.uu5j-vbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.128 2.506 2.506 12.128 2.5 24h0c.006 11.872 9.628 21.495 21.5 21.5h0c11.874 0 21.5-9.626 21.5-21.5S35.874 2.5 24 2.5");
}

.y5xj3-y4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.7 21.07c12.88-2.53 24.72-9 33-15.09M8.27 38.65A75.3 75.3 0 0 0 28.67 32a94 94 0 0 0 16.7-10.36M13.75 5.1a6.73 6.73 0 1 0 13.09-2.41");
}

</style>
