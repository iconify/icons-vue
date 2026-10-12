<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ulqzijnen"/><path class="c7ctqnbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mushroom-sharp" /></template>
<style>
.c7ctqnbzi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8.75h.01m5.49-2h.01M16 10h.01");
}

.ulqzijnen {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.5a8.75 8 0 0 1 17.5 0v1.25H3.25zM9 15h6l.5 4.5l.3 1.775l-1.8-.025h-4l-1.8.025l.3-1.775Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
