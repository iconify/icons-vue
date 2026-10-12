<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qlsejubzq"/><path class="kmwwmbbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pin-heart-outline-sharp" /></template>
<style>
.kmwwmbbex {
  d: path("M12 13.25c-2.25-1.5-3.25-2.6-3.25-3.85A1.63 1.63 0 0 1 12 8.8a1.63 1.63 0 0 1 3.25.6c0 1.25-1 2.35-3.25 3.85Z");
}

.qlsejubzq {
  d: path("M12 21.25C8 17.75 5 14 5 10a7 7 0 0 1 14 0c0 4-3 7.75-7 11.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
