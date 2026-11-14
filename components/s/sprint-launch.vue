<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cewkm6bhi"/><path class="z3qgvx5qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprint-launch" /></template>
<style>
.cewkm6bhi {
  d: path("M20.5 3.5c-4.5 0-9 3-11.5 7l4.5 4.5c4-2.5 7-7 7-11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z3qgvx5qz {
  d: path("M13.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3.25 2.75L4.5 19.5l7.75-5.75M9.75 9.5H6.5l-2 2.5m10 2.25v3.25l-2.5 2");
}

</style>
