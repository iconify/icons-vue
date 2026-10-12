<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="la8whubsv"/><path class="u-jzcpbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:restore-window-sharp" /></template>
<style>
.la8whubsv {
  d: path("M2.75 8.25h13v12h-13zm.75 3.5H15");
}

.u-jzcpbzy {
  d: path("M7.5 8.25v-4.5h13.75v12.5h-5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
