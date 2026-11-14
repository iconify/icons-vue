<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttrgfc1bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-birthday" /></template>
<style>
.ttrgfc1bg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 16h12.75A2.625 2.625 0 0 1 21 18.625v.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-.25A2.625 2.625 0 0 1 5.625 16m2.625-4.5h7.5A2.25 2.25 0 0 1 18 13.75A2.25 2.25 0 0 1 15.75 16h-7.5A2.25 2.25 0 0 1 6 13.75a2.25 2.25 0 0 1 2.25-2.25M12 8.75v2.75m0-9c1 1 1.5 1.5 1.5 2a1.5 1.5 0 0 1-3 0c0-.5.5-1 1.5-2");
}

</style>
