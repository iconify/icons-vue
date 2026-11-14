<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvugj2bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user-crown" /></template>
<style>
.bvugj2bog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5L8 2.75l2.25 1.75l1.75-2l1.75 2L16 2.75l-.5 3.75Zm.5 5.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM4.5 21.5c0-2 3.25-3.25 7.5-3.25s7.5 1.25 7.5 3.25");
}

</style>
