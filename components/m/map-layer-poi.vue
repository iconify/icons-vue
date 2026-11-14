<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iz1dwr8lk"/><path class="hhg1s1hrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-layer-poi" /></template>
<style>
.hhg1s1hrm {
  d: path("M9.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.iz1dwr8lk {
  d: path("M12 21.5c-3-2.75-7.5-7-7.5-11.5a7.5 7.5 0 0 1 15 0c0 4.5-4.5 8.75-7.5 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
