<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au_82y68l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retractor" /></template>
<style>
.au_82y68l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5h18.5m-10.75 0V3.25m3 2.25V3.25M5 5.5v11a2.125 2.125 0 0 0 4.25 0M19 5.5v11a2.125 2.125 0 0 1-4.25 0");
}

</style>
