<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhyg_1gev"/><path class="u8fphpdwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:muscle" /></template>
<style>
.fhyg_1gev {
  d: path("M3.25 19.5c0-3 1.5-5.75 4-7.25L10 5.5c.4-1 1.4-1.75 2.5-1.75h2.25a1.5 1.5 0 0 1 .4 2.95L13 7.5l-1.25 4.25c1.75-1.5 4-2 6-1.25c2.25.85 3 3.25 2.25 5.5c-.9 2.75-3.6 4.25-6.5 4.25H4.75a1.5 1.5 0 0 1-1.5-1.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u8fphpdwj {
  d: path("M11.5 16c1.5-1.25 3.5-1.5 5-.75");
}

</style>
