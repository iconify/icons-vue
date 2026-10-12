<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncyphgbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mammogram-sharp" /></template>
<style>
.ncyphgbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h16.5m-16.5 11.5h16.5m-16.5-8.5C9 9.25 15.5 9.5 15.5 12S9 14.75 2.75 14.75");
}

</style>
