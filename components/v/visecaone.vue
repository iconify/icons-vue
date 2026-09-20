<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="etcqc_kvq"/><rect class="wtavvfctk"/><path class="udk224j8h"/><circle class="xvh_8jbwf"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:visecaone" /></template>
<style>
.etcqc_kvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.343 36.47a3.36 3.36 0 0 1-2.387.99h-.002a3.375 3.375 0 0 1-3.375-3.376v-2.226a3.375 3.375 0 0 1 3.376-3.375h.001a3.375 3.375 0 0 1 3.375 3.375v1.012m0 .101h-6.752");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.udk224j8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.625 31.858a3.374 3.374 0 1 1 6.748 0v5.601m-6.748-8.976v8.976");
}

.wtavvfctk {
  width: 6.748px;
  height: 8.976px;
  x: 10.669px;
  y: 28.483px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.374px;
  ry: 3.374px;
}

.xvh_8jbwf {
  cx: 32.54px;
  cy: 15.46px;
  r: 4.791px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
