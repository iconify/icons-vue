<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mjze8rg7o"/><path class="x3sflacnk"/><path class="yp080mb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retrieval-fallback-outline-bold" /></template>
<style>
.mjze8rg7o {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x3sflacnk {
  d: path("M9 18h6");
}

.yp080mb3n {
  d: path("M11.5 15.5 9 18l2.5 2.5");
}

</style>
