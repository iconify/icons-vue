<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e7pgrp-wx"/><path class="x8p5627ac"/><path class="l2xj1bblk"/><path class="p8a31xr4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tls-outline-bold" /></template>
<style>
.e7pgrp-wx {
  d: path("M2 12h6");
}

.l2xj1bblk {
  d: path("M9 9a3 3 0 0 1 6 0");
}

.p8a31xr4o {
  d: path("M16 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x8p5627ac {
  d: path("M8 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
