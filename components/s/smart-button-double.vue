<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w4jbf3b0d"/><path class="j6loa1oiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-button-double" /></template>
<style>
.j6loa1oiu {
  d: path("M5.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4jbf3b0d {
  d: path("M3.5 4.75h17a1 1 0 0 1 1 1v12.5a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1V5.75a1 1 0 0 1 1-1Z");
}

</style>
