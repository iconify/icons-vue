<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_dmaj-ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:punch-bowl" /></template>
<style>
.j_dmaj-ft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h18c0 5-4 8.5-9 8.5S3 15 3 10Zm9 8.5V21m-3.5 0h7M15 10l3.5-6.5");
}

</style>
