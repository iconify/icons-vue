<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x25towbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-bamboo" /></template>
<style>
.x25towbpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13h12v4c0 2.5-2.5 4.5-6 4.5s-6-2-6-4.5Zm4 0V2.5M14 13V5m0 3.5c1.5-2 4-3 6.5-3c-1.5 2-4 3-6.5 3m-4-2c-1.5-2-4-3-6.5-3c1.5 2 4 3 6.5 3");
}

</style>
