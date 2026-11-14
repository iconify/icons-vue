<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6zfbgbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rugby-jersey" /></template>
<style>
.g6zfbgbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3c0 1.5 1.5 2.5 3 2.5s3-1 3-2.5l5.5 2.75l1 4.75l-4 .5v10h-11V11l-4-.5l1-4.75Zm3 2.5V9m-5.5 5h11");
}

</style>
