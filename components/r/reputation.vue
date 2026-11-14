<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxzl1tbmo"/><path class="ao1oebc5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reputation" /></template>
<style>
.ao1oebc5q {
  d: path("M8.5 15v6l1.75-1.25L12 21l1.75-1.25L15.5 21v-6M12 6l.75 2.25l2.5.25L13.5 10l.5 2.25L12 11l-2 1.25l.5-2.25l-1.75-1.5l2.5-.25Z");
}

.mxzl1tbmo {
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
