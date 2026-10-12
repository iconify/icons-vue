<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhza-zbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sixteenth-note" /></template>
<style>
.zhza-zbrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.99 19.37a4 2.9-20 1 0 7.52-2.74a4 2.9-20 1 0-7.52 2.74m7.52-2.74V2.75m0 0c0 2.75 4.75 3.5 4.75 7m-4.75-3c0 2.75 4.75 3.5 4.75 7");
}

</style>
