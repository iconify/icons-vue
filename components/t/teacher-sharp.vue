<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vkh2p_buw"/><path class="aw3t3lb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teacher-sharp" /></template>
<style>
.aw3t3lb7d {
  d: path("M3.75 21.25v-4.5a3.75 3.75 0 0 1 7.5 0v4.5Zm10-18.5h7.5v9h-7.5zM12 15.25l3.75-3.5");
}

.vkh2p_buw {
  cx: 7.5px;
  cy: 7px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
