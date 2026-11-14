<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x6grj2_cr"/><path class="kvtyuet-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-room" /></template>
<style>
.kvtyuet-j {
  d: path("M7.25 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM6.5 13H14m-4.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4.75 4a5 5 0 0 1 7 0m-5.25 2.25a2.5 2.5 0 0 1 3.5 0M18 21.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6grj2_cr {
  d: path("M11.1 17.5H3V3h14.5v9.8m-11-5.3H14");
}

</style>
