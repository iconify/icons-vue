<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjw7he09i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tidal-zone" /></template>
<style>
.pjw7he09i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6C4 4 5.75 4 7.25 6S10.5 8 12 6s3.25-2 4.75 0S20 8 21.5 6m-19 6c1.5-2 3.25-2 4.75 0s3.25 2 4.75 0s3.25-2 4.75 0s3.25 2 4.75 0m-19 8l19-3");
}

</style>
