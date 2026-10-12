<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_41tvbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pasture-grass" /></template>
<style>
.u_41tvbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19.5C4.5 16 4 13.25 3 11m5 8.5c0-5 .25-8.25-.75-11.5m4.5 11.5c0-6 .5-10.5 1-14m2.75 14c0-4.5.75-7.75 2-10m1.5 10c0-3 .5-5 1.75-6.5m-18 6.5h18.5");
}

</style>
