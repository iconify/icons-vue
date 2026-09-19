<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="n4jx23-cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-magenta" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.n4jx23-cx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 28.696v-9.402l4.706 9.412l4.707-9.398v9.398m2.174-3.882c0-1.3 1.054-2.354 2.353-2.354h0c1.3 0 2.353 1.054 2.353 2.354v3.882m-4.706-6.236v6.236m4.707-3.882c0-1.3 1.053-2.354 2.353-2.354h0c1.3 0 2.353 1.054 2.353 2.354v3.882");
}

</style>
