<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y55gqrbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orthopaedic-boot" /></template>
<style>
.y55gqrbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h7v9.5l5 2.5c1.25.6 2 1.5 2 3v.5h-16V5a2 2 0 0 1 2-2Zm-2 18h16M4.5 9h9");
}

</style>
