<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dr5emhbkc"/><path class="kjzfsabuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wall-clock-modern" /></template>
<style>
.dr5emhbkc {
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.kjzfsabuw {
  d: path("M12 8v4h3M5 5L3 3m16 2l2-2M5 19l-2 2m16-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
