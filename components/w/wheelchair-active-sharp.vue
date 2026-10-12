<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e-8if9bto"/><path class="yakw97yev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheelchair-active-sharp" /></template>
<style>
.e-8if9bto {
  cx: 15.25px;
  cy: 4.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yakw97yev {
  d: path("m14 8.25l-2.5 5h5.25L18.5 19h2.75m-9-9.5h4.25m-8.25 1.1a5.25 5.25 0 1 0 6.35 7.15m-11.85-10h3.5M3.75 11h2");
}

</style>
