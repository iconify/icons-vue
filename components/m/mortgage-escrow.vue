<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_dw6zgso"/><path class="d_av1ib8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-escrow" /></template>
<style>
.d_av1ib8n {
  d: path("M21.5 11L17 6.5h-3L11.5 9M5 13.5l5 5c.582.582 1.316.713 1.965.39M9 12.75L11.25 15m.25-3.75l2 2m1.733 4.055l1.75-1.616a1.5 1.5 0 0 1 2.034 0l1.75 1.616a1.5 1.5 0 0 1 .483 1.102v1.343a1.5 1.5 0 0 1-1.5 1.5h-3.5a1.5 1.5 0 0 1-1.5-1.5v-1.343a1.5 1.5 0 0 1 .483-1.102");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_dw6zgso {
  d: path("M2.5 11L7 6.5h3l4.5 4.5");
}

</style>
