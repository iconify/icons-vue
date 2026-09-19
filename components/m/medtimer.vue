<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-44.72 9.838 8.643)" class="jk2n6fb_b"/><rect transform="rotate(-45.28 30.682 8.652)" class="ve1u5qbtt"/><circle class="mf4a4p8iz"/><path class="jkg_j1bkt"/><circle class="otfq5b21l"/><path class="o-ym81bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medtimer" /></template>
<style>
.jk2n6fb_b {
  width: 6.439px;
  height: 3.216px;
  x: 6.618px;
  y: 7.035px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.64px;
  ry: 0.64px;
}

.jkg_j1bkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.051 27.792l-.765 3.19m15.315-3.19l.765 3.19");
}

.mf4a4p8iz {
  cx: 20.326px;
  cy: 19.415px;
  r: 11.094px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o-ym81bjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.326 11.271v7.087m1.063 1.057h5.084m8.304 6.465a3.639 3.639 0 1 1 5.798 4.397m-8.199 10.781a3.639 3.639 0 0 1-5.8-4.394l.001-.003l8.2-10.781m5.799 4.397l-8.2 10.781m4.1-5.39l-5.799-4.397");
}

.otfq5b21l {
  cx: 20.326px;
  cy: 19.415px;
  r: 1.057px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ve1u5qbtt {
  width: 3.216px;
  height: 6.439px;
  x: 29.074px;
  y: 5.432px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.64px;
  ry: 0.64px;
}

</style>
