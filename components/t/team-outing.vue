<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1iu4jb7r"/><path class="hdf0iubem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-outing" /></template>
<style>
.e1iu4jb7r {
  d: path("m13.525 6.212l6.008 10.68a1.75 1.75 0 0 1-1.525 2.608H5.992a1.75 1.75 0 0 1-1.525-2.608l6.008-10.68a1.75 1.75 0 0 1 3.05 0");
}

.hdf0iubem {
  d: path("m9 19.5l3-6l3 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
