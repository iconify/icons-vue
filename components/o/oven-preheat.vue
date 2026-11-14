<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kubzt7b5c"/><path class="e39nw-jcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oven-preheat" /></template>
<style>
.e39nw-jcn {
  d: path("M8.75 13h6.5A1.75 1.75 0 0 1 17 14.75v2a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 16.75v-2A1.75 1.75 0 0 1 8.75 13M8 7Q6.5 5.875 8 4.75T8 2.5M12 7q-1.5-1.125 0-2.25t0-2.25M16 7q-1.5-1.125 0-2.25t0-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kubzt7b5c {
  d: path("M7 10h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-4.5A3.5 3.5 0 0 1 7 10");
}

</style>
