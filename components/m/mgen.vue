<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="cyuh2bc5b"/><rect transform="matrix(-1 0 0 -1 45.58 49.028)" class="qewlieb5d"/><path class="v4u5fn8ae"/><path class="fe5mtnwmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mgen" /></template>
<style>
.cyuh2bc5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.991 21.598V28.2a2.2 2.2 0 0 1-2.201 2.202a2.2 2.2 0 0 1-1.557-.645");
}

.fe5mtnwmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.903 23.799a2.201 2.201 0 1 1 4.403 0v3.632m13.151-1.111a2.201 2.201 0 0 1-4.114-1.09v-1.431a2.201 2.201 0 0 1 4.403 0v.715h-4.403M38.5 27.43V23.8a2.201 2.201 0 1 0-4.403 0v3.632m0-3.633v-2.201");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
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

.v4u5fn8ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 23.799a2.201 2.201 0 1 1 4.403 0v3.632M9.5 21.598v5.833");
}

</style>
