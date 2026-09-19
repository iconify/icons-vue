<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="otai91_1a"/><rect transform="matrix(-1 0 0 -1 45.58 49.028)" class="qewlieb5d"/><path class="ql9m3i2ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mgen" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.otai91_1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.991 21.598V28.2a2.2 2.2 0 0 1-2.201 2.202h0a2.2 2.2 0 0 1-1.557-.645");
}

.qewlieb5d {
  width: 4.402px;
  height: 5.833px;
  x: 20.589px;
  y: 21.598px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.201px;
  ry: 2.201px;
}

.ql9m3i2ab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 23.799c0-1.216.986-2.202 2.201-2.202h0c1.216 0 2.202.986 2.202 2.202v3.632M9.5 21.598v5.833m4.403-3.632c0-1.216.985-2.202 2.2-2.202h0c1.216 0 2.202.986 2.202 2.202v3.632m13.152-1.111a2.2 2.2 0 0 1-1.913 1.11h0a2.2 2.2 0 0 1-2.201-2.2v-1.431c0-1.216.986-2.201 2.201-2.201h0c1.216 0 2.202.985 2.202 2.2v.716h-4.403M38.5 27.43V23.8a2.2 2.2 0 0 0-2.201-2.202h0a2.2 2.2 0 0 0-2.202 2.202v3.632m0-3.633v-2.201");
}

</style>
