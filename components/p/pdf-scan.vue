<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uwmnfgqzx"/><g class="y9tr6bcfx"><path class="yd7b5_bmo"/><path class="v0vdhsf6u"/></g><path class="v01x9yboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdf-scan" /></template>
<style>
.uwmnfgqzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 10V6.5c0-1.1-.9-2-2-2H34M39.5 38v3.5c0 1.1-.9 2-2 2H34");
}

.v01x9yboz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 10V6.5c0-1.1.9-2 2-2H14m0 39h-3.5c-1.1 0-2-.9-2-2V38");
}

.v0vdhsf6u {
  d: path("M15.976 31.294v-6.896h2.321a2.314 2.314 0 1 1 .002 4.629h-2.323m6.297 2.281v-6.923h1.174a3.46 3.46 0 0 1 3.461 3.461h0a3.46 3.46 0 0 1-3.461 3.462z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yd7b5_bmo {
  d: path("M35.923 17.462H29c-.85 0-1.538-.69-1.538-1.539V9H13.615c-.85 0-1.538.689-1.538 1.538v26.924c0 .85.689 1.538 1.538 1.538h20.77c.85 0 1.538-.689 1.538-1.538zM27.462 9l8.461 8.462m-7.354 6.949h3.455m-3.455 3.449h2.254m-2.254-3.449v6.897");
}

</style>
