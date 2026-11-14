<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lk-0gvbbz"/><path class="hn6kmkgey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:switch-slide" /></template>
<style>
.hn6kmkgey {
  d: path("M5.5 10h5v4h-5Z");
}

.lk-0gvbbz {
  d: path("M5.5 8h13a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
