<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ml8hvsbgr"/><path class="kmuea923i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:software-update-sharp" /></template>
<style>
.kmuea923i {
  d: path("M17.5 14.75a2.75 2.75 0 1 1-2.75 2.75m-1.25 1.25l1.25-1.25L16 18.75");
}

.ml8hvsbgr {
  d: path("M10.75 20.25h-8V3.75h18.5v8m-18.5-3.5h18.5m-15 3.5h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
