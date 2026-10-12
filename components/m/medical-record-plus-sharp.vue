<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nov8h6lvs"/><path class="s-rhocccd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medical-record-plus-sharp" /></template>
<style>
.nov8h6lvs {
  d: path("M2.75 6.25v-2h6.5l2 2.25h10v14.75H2.75v-2Z");
}

.s-rhocccd {
  d: path("M11.5 10.5h1.4v1.85h1.85v1.8H12.9V16h-1.8v-1.85H9.25v-1.8h1.85V10.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
