<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xlnl3xize"/><path class="pthfvvbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sun-snow-sharp" /></template>
<style>
.pthfvvbfo {
  d: path("M9 3.75v-1M3.75 9h-1m2.54-3.71l-.71-.71M14.25 9h1m-2.54-3.71l.71-.71m-8.13 8.13l-.71.71M16.75 13v8m-3.46-6l6.92 4m-6.92 0l6.92-4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlnl3xize {
  cx: 9px;
  cy: 9px;
  r: 3.5px;
}

</style>
