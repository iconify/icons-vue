<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ak5rbbs9u"/><path class="eo--j44-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ridge" /></template>
<style>
.ak5rbbs9u {
  d: path("m2.5 19l6-9l3 4l4-9l6 14Z");
}

.eo--j44-t {
  d: path("m15.5 5l-1.75 5l2 3.5l-1.25 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
