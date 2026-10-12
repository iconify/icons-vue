<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nitjb1frl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quantization" /></template>
<style>
.nitjb1frl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V17.5h4.5V13h4.5V8.5h4.5V4h5m-18.5 9.5C4.5 8.25 8 4 13.25 2.75");
}

</style>
