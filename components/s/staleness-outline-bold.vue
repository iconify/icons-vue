<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sl0tqnboi"/><path class="yf0ac-1wm"/><path class="wuu7accch"/><path class="ennto9b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-outline-bold" /></template>
<style>
.ennto9b9x {
  d: path("M16 16h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sl0tqnboi {
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.wuu7accch {
  d: path("M14 20h7");
}

.yf0ac-1wm {
  d: path("M10 9v3h3");
}

</style>
