<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ye_62_hdn"/><path class="bj1gw2b_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-tracker-sharp" /></template>
<style>
.bj1gw2b_z {
  d: path("M11.61 8.5a3.5 3.5 0 1 0 3.57 4.17a2.75 2.75 0 0 1-3.57-4.17Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye_62_hdn {
  d: path("M8.25 2.75h7.5v3.5h-7.5zm0 15h7.5v3.5h-7.5zm-2.5-11.5h12.5v11.5H5.75z");
}

</style>
