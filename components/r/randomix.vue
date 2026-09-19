<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="okcbqgblm"/><path class="zr498qbhq"/><path class="mzhg1ubsg"/><path class="sggri2bsb"/><path class="uvt9dcc6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:randomix" /></template>
<style>
.mzhg1ubsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.78 4.11a3.88 3.88 0 1 0 6.45 0M24 24c-4.84-4.84-6.88-8.48-11.72-8.48a8.53 8.53 0 1 0 0 17.05");
}

.okcbqgblm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.89V16.11M16.11 24h15.78M24 24c-4.84 4.84-8.48 6.88-8.48 11.72a8.53 8.53 0 1 0 17.05 0");
}

.sggri2bsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.11 27.22a3.88 3.88 0 1 0 0-6.45M24 24c4.84 4.84 6.88 8.48 11.72 8.48a8.53 8.53 0 1 0 0-17");
}

.uvt9dcc6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.89 20.78a3.88 3.88 0 1 0 0 6.45");
}

.zr498qbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.22 43.89a3.88 3.88 0 1 0-6.45 0M24 24c4.84-4.84 8.48-6.88 8.48-11.72a8.53 8.53 0 1 0-17 0");
}

</style>
