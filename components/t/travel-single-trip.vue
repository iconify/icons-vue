<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovx--2pli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:travel-single-trip" /></template>
<style>
.ovx--2pli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5c.75 0 1 .5 1 1.5v3.5l5.75 3.5v1.5l-5.75-1.75V14l2 1.25v1.25l-3-.75l-3 .75v-1.25l2-1.25v-3.25L2.75 12.5V11L8.5 7.5V4c0-1 .25-1.5 1-1.5Zm7.25 14L18.5 15v6");
}

</style>
