<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jfs11lnas"/><path class="kuaoi3hpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stock-chart-up-sharp" /></template>
<style>
.jfs11lnas {
  d: path("M3.75 3.75v16.5h17M8 17.25V14m4.5 3.25V12m4.5 5.25V10");
}

.kuaoi3hpx {
  d: path("m6.75 10.25l4-4l2.5 2.5l5.5-5.5m-3 0h3v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
