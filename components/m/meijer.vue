<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fpwglsbzd"/><circle class="ahgh3c-sl"/><path class="omj2xdbra"/><circle class="x-swfybme"/><path class="bv-yowb5h"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meijer" /></template>
<style>
.ahgh3c-sl {
  cx: 25.131px;
  cy: 19.517px;
  r: 0.75px;
  fill: currentColor;
}

.bv-yowb5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.141 25.708c-.286.572-.952.953-1.62.953h0a1.91 1.91 0 0 1-1.904-1.905v-1.238a1.91 1.91 0 0 1 1.905-1.905h0a1.91 1.91 0 0 1 1.905 1.905v.666h-3.81m5.978-.666a1.91 1.91 0 0 1 1.905-1.905h0m-1.905 0v5.143");
}

.fpwglsbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 23.518a1.91 1.91 0 0 1 1.905-1.905h0a1.91 1.91 0 0 1 1.905 1.905v3.143M9.5 21.613v5.143m3.81-3.238a1.91 1.91 0 0 1 1.905-1.905h0a1.91 1.91 0 0 1 1.905 1.905v3.143m5.592-.953c-.286.572-.953.953-1.62.953h0a1.91 1.91 0 0 1-1.904-1.905v-1.238a1.91 1.91 0 0 1 1.904-1.905h0a1.91 1.91 0 0 1 1.905 1.905v.666h-3.81");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.omj2xdbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.131 21.613v5.143m3.239-5.143v5.715a1.91 1.91 0 0 1-1.906 1.905h0a1.88 1.88 0 0 1-1.333-.572");
}

.x-swfybme {
  cx: 28.369px;
  cy: 19.517px;
  r: 0.75px;
  fill: currentColor;
}

</style>
