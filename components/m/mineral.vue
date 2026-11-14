<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epmau3bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mineral" /></template>
<style>
.epmau3bcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.115 4.239l2.86 3.178a1.5 1.5 0 0 1 .345 1.347l-1.548 6.58a1.5 1.5 0 0 1-1.46 1.156h-2.624a1.5 1.5 0 0 1-1.46-1.156L7.68 8.764a1.5 1.5 0 0 1 .345-1.347l2.86-3.178a1.5 1.5 0 0 1 2.23 0M3.5 21l3-4.5h11l3 4.5ZM12 3v13.5");
}

</style>
