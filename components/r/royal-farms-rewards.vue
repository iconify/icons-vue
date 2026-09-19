<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lp4uibbpf"/><rect class="qt8-gfjlm"/><rect class="g7cyhmh2w"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:royal-farms-rewards" /></template>
<style>
.g7cyhmh2w {
  width: 7.346px;
  height: 11.088px;
  x: 25.275px;
  y: 25.412px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.673px;
  ry: 3.673px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lp4uibbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.38 22.588V11.5h3.63c2.051 0 3.715 1.667 3.715 3.724s-1.664 3.724-3.716 3.724h-3.63m3.63 0l3.63 3.637m-7.26 8.371h3.604M15.379 36.5V25.412h5.544");
}

.qt8-gfjlm {
  width: 7.346px;
  height: 11.088px;
  x: 25.275px;
  y: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.673px;
  ry: 3.673px;
}

</style>
