<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n48w5yb-p"/><path class="x26a8iq1c"/><path class="wshbdfbhg"/><path class="s-gg8lbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:table-rows-split-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n48w5yb-p {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.s-gg8lbxh {
  d: path("m9.5 15 2.5 2.5 2.5 -2.5");
}

.wshbdfbhg {
  d: path("M9.5 9 12 6.5 14.5 9");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

</style>
