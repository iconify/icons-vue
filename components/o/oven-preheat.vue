<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hwqs9ib3b"/><path class="dc7lr8boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oven-preheat" /></template>
<style>
.dc7lr8boj {
  d: path("M7 13h10v5.5H7Zm1-6Q6.5 5.875 8 4.75T8 2.5M12 7q-1.5-1.125 0-2.25t0-2.25M16 7q-1.5-1.125 0-2.25t0-2.25");
}

.hwqs9ib3b {
  d: path("M3.5 10h17v11.5h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
