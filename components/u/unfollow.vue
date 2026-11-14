<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr0vcrtsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:unfollow" /></template>
<style>
.hr0vcrtsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2 21.5c0-2.5 1.25-3 3-3s3 .5 3 3m8.5-8.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 21.5c0-2.5 1.25-3 3-3s3 .5 3 3M10 3H8a2.5 2.5 0 0 0 0 5h2m4-5h2a2.5 2.5 0 0 1 0 5h-2m-2-6v1.25m0 4.5V9");
}

</style>
