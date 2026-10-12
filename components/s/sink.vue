<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdmr5xbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sink" /></template>
<style>
.tdmr5xbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.75h18.5a6 6 0 0 1-6 6h-6.5a6 6 0 0 1-6-6m9.25 6v3.5m-2.25-9.5V6a2.25 2.25 0 0 1 4.5 0v.75");
}

</style>
