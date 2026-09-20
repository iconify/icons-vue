<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c5icmybsm"/><path class="avartybbb"/><path class="gvu3jzbph"/><path class="phup74asp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:semantic-version-outline-bold" /></template>
<style>
.avartybbb {
  d: path("M11 9.5v5");
}

.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.gvu3jzbph {
  d: path("M14 9.5v5");
}

.phup74asp {
  d: path("M17 9.5v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
