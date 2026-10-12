<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c27qgbcgm"/><path class="h5u1zbbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salamander-sharp" /></template>
<style>
.c27qgbcgm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.25c0-1.75 1.5-3 3.25-3h1.75L9 10.5h8.643L20 13.25l1 1.25l.698.837L20.6 15.2c-1.6-.2-3.6-.7-6.1-.7H9l-1.25 1.25H6c-1.75 0-3.25-1.5-3.25-3.5ZM9.5 14.5L8 17.75m7.25-3.25l1 3.25");
}

.h5u1zbbrr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.5h.01m3.49 0h.01m-9.76-1h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
