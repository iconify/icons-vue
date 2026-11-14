<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bgl4vo-oo"/><path class="mti0imbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pivot-fields" /></template>
<style>
.bgl4vo-oo {
  d: path("M4.75 2.5h8.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 13.25 7h-8.5A2.25 2.25 0 0 1 2.5 4.75A2.25 2.25 0 0 1 4.75 2.5m0 6.75h8.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-8.5A2.25 2.25 0 0 1 2.5 11.5a2.25 2.25 0 0 1 2.25-2.25m0 6.75h5A2.25 2.25 0 0 1 12 18.25a2.25 2.25 0 0 1-2.25 2.25h-5a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 4.75 16M5.5 4.75h3m-3 6.75h3m-3 6.75H8m7.25 3.25V19a3 3 0 0 1 3-3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mti0imbma {
  d: path("M19.5 14.25L21.25 16l-1.75 1.75");
}

</style>
