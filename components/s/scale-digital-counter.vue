<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kca3lkaou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scale-digital-counter" /></template>
<style>
.kca3lkaou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.603 18.29l.545-2A1.75 1.75 0 0 1 5.837 15h12.326a1.75 1.75 0 0 1 1.689 1.29l.545 2a1.75 1.75 0 0 1-1.688 2.21H5.291a1.75 1.75 0 0 1-1.688-2.21M4.5 12.5h15m-7.5-4v4M8.75 3h6.5A1.75 1.75 0 0 1 17 4.75v2a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 6.75v-2A1.75 1.75 0 0 1 8.75 3m.75 2.75h5");
}

</style>
