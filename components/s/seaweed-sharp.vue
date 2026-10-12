<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6qjscc4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seaweed-sharp" /></template>
<style>
.p6qjscc4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5q-2.25-3 0-6c2.25-3 1.5-4 0-6S5.5 4.75 7 2.75m5.5 17.75q2.25-3 0-6c-2.25-3-1.5-4 0-6s1.5-3 .5-4.75m4.5 16.75c-1.25-1.75-1.25-3.25 0-5s1.25-3.25 0-5M2.75 21.25h18.5");
}

</style>
