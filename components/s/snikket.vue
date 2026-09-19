<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g856fw_bl"/><path class="g_-6oj73i"/><path class="b5p1aac0l"/><path class="flcq00wei"/><circle class="sxey0sbxj"/><path class="q2uacokxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snikket" /></template>
<style>
.b5p1aac0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.011 23.3a21.5 21.5 0 0 1 18.81 11.1");
}

.flcq00wei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.286 28.734a21.515 21.515 0 0 1-24.263 2.981");
}

.g_-6oj73i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 42.624a21.507 21.507 0 0 1 0-37.248");
}

.g856fw_bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 42.624a21.488 21.488 0 1 1 8.072-8.224");
}

.q2uacokxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.804 13.617a1.556 1.556 0 0 1-1.264-2.47a3 3 0 0 0-.297-.03a2.5 2.5 0 1 0 2.5 2.5a3 3 0 0 0-.03-.297a1.55 1.55 0 0 1-.91.297M4.481 33.041a11.9 11.9 0 0 1 1.017 4.839a11.94 11.94 0 0 1-2.633 7.49a12 12 0 0 0 1.671.13a11.96 11.96 0 0 0 8.165-3.205");
}

.sxey0sbxj {
  cx: 17.243px;
  cy: 13.617px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
