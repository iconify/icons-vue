<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1drf-d7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:surfboard-marine" /></template>
<style>
.u1drf-d7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75c2.25 0 3.5 4 3.5 8.75s-1.25 7.25-3.5 7.25s-3.5-3-3.5-7.25S6 2.75 8.25 2.75m0 3v10m5.5 4c.75-4.25 3-7.75 6-7.75c1 0 1.5.5 1.5 1.25s-.75 1.5-1.75 1.5m-16.75 6.5h18.5");
}

</style>
