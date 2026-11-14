<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jb7nsmb_z"/><path class="e3v9__bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trachea" /></template>
<style>
.e3v9__bad {
  d: path("M9 5c1.75 1 4.25 1 6 0M9.25 8.75c1.5 1 4 1 5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb7nsmb_z {
  d: path("M9 2.5L9.5 13c0 1.75-1.5 3.5-4 6.5m9.5-17L14.5 13c0 1.75 1.5 3.5 4 6.5m-10 2L12 17l3.5 4.5");
}

</style>
