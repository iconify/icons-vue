<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hdqgxt26r"/><circle class="ua9o6gydm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:valley-sharp" /></template>
<style>
.hdqgxt26r {
  d: path("M2.75 21.25V10C6.5 11 9 14.5 10 21.25Zm18.5 0V12.5c-3.25.75-5.75 3.75-6.75 8.75Zm-9-8.5c-.75 1.5.75 2.75 0 4.25s.5 2.75 0 4.25");
}

.ua9o6gydm {
  cx: 16.5px;
  cy: 6px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
