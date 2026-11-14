<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5rvxxbgs"/><path class="ych71wguk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stegosaurus" /></template>
<style>
.d5rvxxbgs {
  d: path("M2.75 14c0-1.25 1-1.75 2.25-1.25C7 9.5 14 8.5 17.5 11.5l3.25 2l-3.75 1c-2 1.5-8 1.5-10.5.25L3.75 15c-.75 0-1-.5-1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ych71wguk {
  d: path("M6.75 11L8 7.5L9.25 10L11 6l1.25 3.75L14 7l1 3.25M8 15.5V19m6.5-3.5V19m4.25-6.75l.5-2.25m.75 2.75L21 11");
}

</style>
