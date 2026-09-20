<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p17gnmb2k"/><circle class="ahgh3c-sl"/><path class="i0511ebqv"/><circle class="x-swfybme"/><path class="vs80liznf"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meijer" /></template>
<style>
.ahgh3c-sl {
  cx: 25.131px;
  cy: 19.517px;
  r: 0.75px;
  fill: currentColor;
}

.i0511ebqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.131 21.613v5.143m3.239-5.143v5.715a1.91 1.91 0 0 1-1.906 1.905a1.88 1.88 0 0 1-1.333-.572");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.p17gnmb2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 23.518a1.91 1.91 0 0 1 1.905-1.905a1.91 1.91 0 0 1 1.905 1.905v3.143M9.5 21.613v5.143m3.81-3.238a1.91 1.91 0 0 1 1.905-1.905a1.91 1.91 0 0 1 1.905 1.905v3.143m5.592-.953c-.286.572-.953.953-1.62.953a1.91 1.91 0 0 1-1.904-1.905v-1.238a1.91 1.91 0 0 1 1.904-1.905a1.91 1.91 0 0 1 1.905 1.905v.666h-3.81");
}

.vs80liznf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.141 25.708c-.286.572-.952.953-1.62.953a1.91 1.91 0 0 1-1.904-1.905v-1.238a1.91 1.91 0 0 1 1.905-1.905a1.91 1.91 0 0 1 1.905 1.905v.666h-3.81m5.978-.666a1.91 1.91 0 0 1 1.905-1.905m-1.905 0v5.143");
}

.x-swfybme {
  cx: 28.369px;
  cy: 19.517px;
  r: 0.75px;
  fill: currentColor;
}

</style>
