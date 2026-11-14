<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kg-44fb7x"/><path class="h-ormzb6m"/><path class="bh8737n7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wire" /></template>
<style>
.bh8737n7a {
  d: path("M16.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.h-ormzb6m {
  d: path("M5 7.5c0 7.5 14 1.5 14 9");
}

.kg-44fb7x {
  d: path("M2.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
