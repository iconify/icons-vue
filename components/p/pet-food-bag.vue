<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pqw9akblk"/><path class="kek1z9-1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-food-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kek1z9-1j {
  d: path("M9.5 12.75h5A1.25 1.25 0 1 1 15.75 14a1.25 1.25 0 1 1-1.25 1.25h-5A1.25 1.25 0 1 1 8.25 14a1.25 1.25 0 1 1 1.25-1.25");
}

.pqw9akblk {
  d: path("m5.5 7l-1 12.5A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-1.5L18.5 7M6.25 3.5h11.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 17.75 7H6.25A1.75 1.75 0 0 1 4.5 5.25A1.75 1.75 0 0 1 6.25 3.5");
}

</style>
