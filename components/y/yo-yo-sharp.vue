<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t2fzt3box"/><circle class="e9-7-8-2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yo-yo-sharp" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.t2fzt3box {
  d: path("M6.5 9.25h2.75V14h5.5v-2a2.75 2.75 0 0 1 5.5 0v6.5a2.75 2.75 0 0 1-5.5 0v-2h-5.5v2a2.75 2.75 0 0 1-5.5 0V9.25zM12 14V6.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
