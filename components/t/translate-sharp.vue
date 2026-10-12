<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yna6unuev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:translate-sharp" /></template>
<style>
.yna6unuev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.75h9m-4.5-2v2m2.75 0c-.6 3.65-3 6.5-6.75 8m2.25-4.5l1.459 2.554L10.75 13m2 7.25l3.75-9l3.75 9m-6.25-3h5");
}

</style>
