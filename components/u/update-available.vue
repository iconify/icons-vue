<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rl70ebcsa"/><path class="pv97iewnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:update-available" /></template>
<style>
.pv97iewnz {
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5 11.5v-9M8.5 11L12 7.5l3.5 3.5");
}

.rl70ebcsa {
  d: path("M21.356 10.35a9.5 9.5 0 1 1-7.706-7.706");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
