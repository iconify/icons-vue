<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ol2p67bps"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parallelogram-sharp" /></template>
<style>
.ol2p67bps {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.75h11.5l-.71 1.87l-4.08 10.76l-.71 1.87H2.5l.71-1.87L7.29 6.62L8 4.75z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
