<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sgdt4_0wi"/><path class="s09hy0b0y"/><path class="c6uw-ccfl"/><path class="kkid9bb2e"/><path class="spncj1b6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:surgery-outline-bold" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.kkid9bb2e {
  d: path("M5 14a3 3 0 0 1 0 -6");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sgdt4_0wi {
  d: path("M5 8h14v5a7 5 0 0 1 -14 0Z");
}

.spncj1b6w {
  d: path("M19 8a3 3 0 0 1 0 6");
}

</style>
