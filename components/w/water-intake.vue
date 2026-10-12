<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cd79rebaw"/><path class="v4an45t_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-intake" /></template>
<style>
.cd79rebaw {
  d: path("M4.25 4.75h8q1.5 0 1.39 1.5l-1.03 13.5q-.11 1.5-1.61 1.5H5.75q-1.5 0-1.64-1.49L2.89 6.24q-.14-1.49 1.36-1.49");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4an45t_e {
  d: path("M3.4 11.75c1.6.9 3.3.9 4.9 0s3.3-.9 4.9 0m5.55-9c1.25 1.75 2.5 3.15 2.5 4.4a2.5 2.5 0 0 1-5 0c0-1.25 1.25-2.65 2.5-4.4");
}

</style>
