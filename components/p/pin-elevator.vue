<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="p0cm1mp5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-elevator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

.p0cm1mp5o {
  d: path("M13.061 6.561L14.25 7.75a1.318 1.318 0 0 1-.932 2.25h-2.636a1.318 1.318 0 0 1-.932-2.25l1.189-1.189a1.5 1.5 0 0 1 2.122 0M10.682 14h2.636a1.318 1.318 0 0 1 .932 2.25l-1.189 1.189a1.5 1.5 0 0 1-2.122 0L9.75 16.25a1.318 1.318 0 0 1 .932-2.25");
}

</style>
