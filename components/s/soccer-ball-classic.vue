<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="yd0jzb8yu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-ball-classic" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yd0jzb8yu {
  d: path("m12 8.5l3.25 2.5L14 14.75h-4L8.75 11ZM8.75 3L12 5l3.25-2m4.25 3.25l-.75 3.5l2.75 2.5m-1.75 5l-3.75.5L14.5 21m-5 0L8 17.75l-3.75-.5m-1.75-5l2.75-2.5l-.75-3.5");
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
