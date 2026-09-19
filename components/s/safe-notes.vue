<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><g class="y9tr6bcfx"><path class="pi6b3oy1b"/><path class="e686br0nh"/><circle class="yf1e9bbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:safe-notes" /></template>
<style>
.e686br0nh {
  d: path("M19.192 23.804V21.79a4.805 4.805 0 0 1 9.608 0v2.014");
}

.pi6b3oy1b {
  d: path("M17.612 23.804h12.776c.484 0 .877.392.877.877v9.442a.877.877 0 0 1-.877.877H17.612a.877.877 0 0 1-.877-.877V24.68c0-.485.393-.878.877-.878");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yf1e9bbgt {
  cx: 23.996px;
  cy: 29.402px;
  r: 1.863px;
}

</style>
