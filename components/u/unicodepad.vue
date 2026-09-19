<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dw8cijbnt"/><path class="b0dbe_b_m"/><path class="vmodfob9g"/><circle class="k0fzqhghx"/><circle class="b8vnr5b3s"/><path class="h2b9ghsno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unicodepad" /></template>
<style>
.b0dbe_b_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.316 40.677H6.755l1.907-13.888c2.76-20.107 34.085-14.994 32.749 5.185c-8.383 4.177-28.296.523-32.75-5.185");
}

.b8vnr5b3s {
  cx: 29.61px;
  cy: 25.884px;
  r: 1.467px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dw8cijbnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.485 33.181a2.058 2.058 0 0 1-2.075-2.513l1.39-20.61c.116-1.715 1.423-3.449 4.518-3.404a3.692 3.692 0 0 1 3.87 4.19l-.36 5.524");
}

.h2b9ghsno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.435 31.392l-.115 2.733");
}

.k0fzqhghx {
  cx: 16.166px;
  cy: 21.85px;
  r: 1.467px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vmodfob9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.316 38.66v2.017h10.083V38.66s.203-4.477-5.042-4.438s-5.041 4.438-5.041 4.438M20.762 14.121l.24-6.004m16.342 11.421l4.331-3.834");
}

</style>
