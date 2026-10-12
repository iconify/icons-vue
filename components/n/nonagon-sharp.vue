<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tft99_bkb"/><path class="fstvu4bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nonagon-sharp" /></template>
<style>
.fstvu4bvg {
  d: path("M14.25 10.5a2.25 2.25 0 1 1-4.5 0a2.25 2.25 0 1 1 4.5 0v5.75H11");
}

.tft99_bkb {
  d: path("m12.47 3.22l5.01 1.82l.47.17l.25.44l2.66 4.61l.25.43l-.09.5l-.92 5.24l-.09.49l-.38.33l-4.08 3.42l-.39.32H8.84l-.39-.32l-4.08-3.42l-.38-.32l-.09-.5l-.92-5.24l-.09-.5l.25-.43L5.8 5.65l.25-.44l.47-.17l5.01-1.82l.47-.17z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
