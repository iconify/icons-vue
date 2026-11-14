<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="so4razbtb"/><path class="jzxu2jn8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rocky-coast" /></template>
<style>
.jzxu2jn8y {
  d: path("M2.5 21q2.5-2 5 0t5 0t5 0t4 0");
}

.so4razbtb {
  d: path("M2.5 13.5L4 7l3.5-3l2 3.5l2.5-4L15 9l.5 4.5Zm0 4q2.5-2 5 0t5 0t5 0t4 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
