<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="bwdnewy5t"/><path class="j-q1rfb8b"/><path class="h1h08f6go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tail-sampling-outline-regular" /></template>
<style>
.bwdnewy5t {
  d: path("M6 12h4.5");
}

.h1h08f6go {
  d: path("M15 12v3");
}

.j-q1rfb8b {
  d: path("m12 9 3 3 3 -3");
}

.lqcp5xb1v {
  d: path("M4 3h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t3vzob-fn {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

</style>
