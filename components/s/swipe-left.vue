<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2qfoh4li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swipe-left" /></template>
<style>
.w2qfoh4li {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 16v-5.5a1.25 1.25 0 0 1 2.5 0V14h1.75a2.5 2.5 0 0 1 2.5 2.5v.5A4.25 4.25 0 0 1 16 21.25h-.75a3.75 3.75 0 0 1-3.75-3.75V17a1 1 0 0 1 1-1Zm2.5-1.5v2.25M18.25 5h-14m2.5-2.25L4.25 5l2.5 2.25");
}

</style>
