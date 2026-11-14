<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="he_2_9czf"/><path class="x1day22vu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-down" /></template>
<style>
.he_2_9czf {
  d: path("M6 2.5h12v19H6ZM10.5 18h3M12 6.5V13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1day22vu {
  d: path("M9.5 10.5L12 13l2.5-2.5");
}

</style>
