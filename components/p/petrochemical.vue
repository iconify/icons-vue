<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xva94qbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:petrochemical" /></template>
<style>
.xva94qbuc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h4.75A2.625 2.625 0 0 1 12.5 5.625v12.75A2.625 2.625 0 0 1 9.875 21h-4.75A2.625 2.625 0 0 1 2.5 18.375V5.625A2.625 2.625 0 0 1 5.125 3M2.5 9h10m-10 6h10m6-2.5s-2.75 3.25-2.75 5.25a2.75 2.75 0 0 0 5.5 0c0-2-2.75-5.25-2.75-5.25");
}

</style>
