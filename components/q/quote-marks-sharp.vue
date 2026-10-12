<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_m4tbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quote-marks-sharp" /></template>
<style>
.oi_m4tbhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11h6.75v7.75H3.5zm1.25 0l.375-4.125L9.25 5.75M13.5 11h6.75v7.75H13.5zm1.25 0l.375-4.125L19.25 5.75");
}

</style>
