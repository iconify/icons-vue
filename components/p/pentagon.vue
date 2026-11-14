<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqlpa2b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pentagon" /></template>
<style>
.gqlpa2b-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.543 4.121l6.187 4.495a2.625 2.625 0 0 1 .953 2.935l-2.363 7.273a2.625 2.625 0 0 1-2.496 1.814H8.176a2.625 2.625 0 0 1-2.496-1.814l-2.363-7.273a2.625 2.625 0 0 1 .953-2.935l6.187-4.495a2.625 2.625 0 0 1 3.086 0");
}

</style>
