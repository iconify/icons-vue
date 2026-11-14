<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="grwnm7rmh"/><path class="jkjz5bc5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wing-nut" /></template>
<style>
.grwnm7rmh {
  d: path("M8.5 12h7v6h-7Z");
}

.jkjz5bc5f {
  d: path("M8.5 15C5.5 15 3 11 3 6.5c3.5 1 6 3 6.5 5.5m6 3c3 0 5.5-4 5.5-8.5c-3.5 1-6 3-6.5 5.5M12 18v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
