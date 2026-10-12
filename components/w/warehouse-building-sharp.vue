<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tzvmh1l8q"/><path class="zqk0_sb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warehouse-building-sharp" /></template>
<style>
.tzvmh1l8q {
  d: path("M2.75 21.25V11a9.25 7.25 0 0 1 18.5 0v10.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zqk0_sb3k {
  d: path("M5.75 21.25v-6h5v6m2.5 0v-6h5v6M9.5 8h5v2.5h-5z");
}

</style>
