<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s9d8etblz"/><path class="a4-ndobqs"/><path class="hdgtvjeta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whale-sharp" /></template>
<style>
.a4-ndobqs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14h.01");
}

.hdgtvjeta {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 17c2.25.75 5.25.75 8.25-.5");
}

.s9d8etblz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13v-2.5h11.857l2.143 3l1.5-3l-1.5-.75v-2h1.5L20 9l.438-1.75h.812v4.417L20 12.5L19 16c-1.5 3-4.5 4.75-8 4.75c-4.5 0-7.75-3.25-7.75-7.75ZM7.5 7.5V5.35l-2-1.6m2 3.75V5.35l2-1.6m-2 3.75V3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
