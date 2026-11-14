<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n_dw6zgso"/><path class="o8ztd-ltf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-escrow" /></template>
<style>
.n_dw6zgso {
  d: path("M2.5 11L7 6.5h3l4.5 4.5");
}

.o8ztd-ltf {
  d: path("M21.5 11L17 6.5h-3L11.5 9M5 13.5l5 5c.582.582 1.316.713 1.965.39M9 12.75L11.25 15m.25-3.75l2 2m1.25 4.5l3.25-3l3.25 3v3.5h-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
