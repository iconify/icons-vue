<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n39y55b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:star-bright" /></template>
<style>
.n39y55b3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 6l1.5 4l4.25.25l-3.25 2.5l1 4L12 14.5l-3.5 2.25l1-4l-3.25-2.5L10.5 10Zm4.75-.5l1-1.5m1.75 10.5l2 .5M12 20v2m-7.5-7.5l-2 .5m4.75-9.5l-1-1.5");
}

</style>
