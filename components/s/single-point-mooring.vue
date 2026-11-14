<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nev7uww6z"/><path class="rbwedcb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:single-point-mooring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nev7uww6z {
  d: path("M7 8.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.rbwedcb5p {
  d: path("M2.5 11.75q1.75-1.5 3.5 0q1.25 1 2.5 0m7 0q1.25-1 2.5 0q1.75 1.5 3.5 0m-9.5 1.5V15m0 2.5V19m0 2.25v.25");
}

</style>
