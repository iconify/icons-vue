<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vsugvlu3y"/><circle class="sbj788ubb"/><path class="kczq9wvdp"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ratio" /></template>
<style>
.kczq9wvdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.3 20.4v7.7m-4.3-10v10m-1.5-7.7h3m-5.9 4.8c0 1.6-1.3 2.9-2.9 2.9h0c-1.6 0-2.9-1.3-2.9-2.9h0v-1.9c0-1.6 1.3-2.9 2.9-2.9h0c1.6 0 2.9 1.3 2.9 2.9h0m0 4.8v-7.7");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.sbj788ubb {
  cx: 29.3px;
  cy: 16.9px;
  r: 0.8px;
  fill: currentColor;
}

.vsugvlu3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 20.4c1.6 0 2.9 1.3 2.9 2.9v1.9c0 1.6-1.3 2.9-2.9 2.9h0c-1.6 0-2.9-1.3-2.9-2.9v-1.9c0-1.6 1.3-2.9 2.9-2.9M10 23.3c0-1.6 1.3-2.9 2.9-2.9h0m-2.9 0v7.7");
}

</style>
