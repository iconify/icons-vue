<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gu-qtlbgb"/><path class="b9hi5l-6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:methane-detector" /></template>
<style>
.b9hi5l-6x {
  d: path("M7.25 8.25h5v4.5h-5ZM18.75 14C19 16 21 17 21 18.5a3 3 0 0 1-6 0c0-1.5 1-2.25 1.5-3c.75.75 1.25 0 2.25-1.5Z");
}

.gu-qtlbgb {
  d: path("M13 21.5H4.5v-16H15v7.2M7.25 5.5v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
