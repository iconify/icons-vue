<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="agjyaybtv"/><path class="k08upyb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shelter" /></template>
<style>
.agjyaybtv {
  d: path("m12.6 4.59l8.05 14.57q.6 1.09-.65 1.09H4q-1.25 0-.65-1.09L11.4 4.59q.6-1.09 1.2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k08upyb9l {
  d: path("m12 11.5l3.5 8.75h-7Z");
}

</style>
