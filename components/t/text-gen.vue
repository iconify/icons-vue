<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edyvdlv-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-gen" /></template>
<style>
.edyvdlv-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.25h14M3.5 10h10m-10 4.75h6m-6 4.75H8m8.5-8.5q.57 4.18 4.75 4.75q-4.18.57-4.75 4.75q-.57-4.18-4.75-4.75q4.18-.57 4.75-4.75");
}

</style>
