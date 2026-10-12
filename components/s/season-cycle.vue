<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpnpfkblo"/><path class="x8ij9qbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:season-cycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8ij9qbzi {
  d: path("M8.75 15.25c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5");
}

.zpnpfkblo {
  d: path("M4.01 9.09a8.5 8.5 0 0 1 15.98 0m-2.04-.95l2.04.95l.95-2.04m-.95 7.86a8.5 8.5 0 0 1-15.98 0m2.04.95l-2.04-.95l-.95 2.04");
}

</style>
