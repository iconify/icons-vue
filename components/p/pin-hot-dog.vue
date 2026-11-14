<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y11wht7ov"/><path class="i_7dmc9lu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-hot-dog" /></template>
<style>
.i_7dmc9lu {
  d: path("M7.5 12q1.25-1 2.5 0t2.5 0t2.5 0t2.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y11wht7ov {
  d: path("M3.5 9h17a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1ZM6 9c0-2 2-3.5 4.5-3.5h3C16 5.5 18 7 18 9M6 15c0 2 2 3.5 4.5 3.5h3C16 18.5 18 17 18 15");
}

</style>
