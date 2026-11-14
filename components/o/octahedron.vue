<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uui4v6bhn"/><path class="gqrrg154p"/><path class="aujcgoije"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:octahedron" /></template>
<style>
.aujcgoije {
  d: path("m12 2.5l-1.5 11l1.5 8");
}

.gqrrg154p {
  d: path("m4 11l6.5 2.5L20 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uui4v6bhn {
  d: path("m13.274 3.854l5.709 6.066a1.75 1.75 0 0 1 .118 2.26l-5.709 7.493a1.75 1.75 0 0 1-2.784 0L4.899 12.18a1.75 1.75 0 0 1 .118-2.26l5.709-6.066a1.75 1.75 0 0 1 2.548 0");
}

</style>
