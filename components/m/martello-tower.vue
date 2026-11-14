<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvetqnbdp"/><path class="dp9hi1b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:martello-tower" /></template>
<style>
.dp9hi1b5p {
  d: path("M10.5 16.5v-3a1.5 1.5 0 0 1 3 0v3M3 20.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvetqnbdp {
  d: path("M8.482 4.5h7.036a1.75 1.75 0 0 1 1.726 1.462l1.416 8.5a1.75 1.75 0 0 1-1.726 2.038H7.066a1.75 1.75 0 0 1-1.726-2.038l1.416-8.5A1.75 1.75 0 0 1 8.482 4.5M6.5 7.5h11");
}

</style>
