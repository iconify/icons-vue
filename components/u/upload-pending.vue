<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ub6jbybsc"/><path class="lu0dhdb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:upload-pending" /></template>
<style>
.lu0dhdb5q {
  d: path("M18 16.5V18l1 1");
}

.ub6jbybsc {
  d: path("M4 15v3a2 2 0 0 0 2 2h6.25M12 15V3.5M7.5 8L12 3.5L16.5 8M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
