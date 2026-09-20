<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzpsuduik"/><path class="cl924fb_o"/><path class="bd3-a5q0s"/><path class="t-3b9ybzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:texture-gen-outline-thin" /></template>
<style>
.bd3-a5q0s {
  d: path("M6 18 18 6");
}

.cl924fb_o {
  d: path("m6 12 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.t-3b9ybzs {
  d: path("m12 18 6 -6");
}

</style>
