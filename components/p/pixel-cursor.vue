<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8kuep3ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pixel-cursor" /></template>
<style>
.r8kuep3ql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3v15.5h2.5V16h2.5v2.5h2.5V21h5v-2.5h-2.5V16h2.5v-2.5h-2.5V11h-2.5V8.5h-2.5V6h-2.5V3Zm5 13h5");
}

</style>
