<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7g2teeeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recycle-loop-sharp" /></template>
<style>
.w7g2teeeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.36 10.3l2.6-4.5L12 4l1.04 1.8l2.77 4.8m.56-2.44l-.56 2.44l-2.39-.73m3.6 2.83l2.6 4.5l1.04 1.8h-7.62m1.83 1.7L13.04 19l1.83-1.7M10.61 19H3.34l1.04-1.8l2.77-4.8m-2.39.73l2.39-.73l.56 2.44");
}

</style>
