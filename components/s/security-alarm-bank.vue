<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvbdx2byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-alarm-bank" /></template>
<style>
.yvbdx2byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 17a6 6 0 0 1 12 0M3.5 17h17v4h-17ZM12 3v3.5m-6.75-.75l2 2m11.5-2l-2 2M2.5 12h2.25m14.5 0h2.25");
}

</style>
