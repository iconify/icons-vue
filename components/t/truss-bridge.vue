<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5f84fo4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:truss-bridge" /></template>
<style>
.l5f84fo4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.75v11.5m10.5-11.5v11.5m-14.5 0h18.5M2.75 11l4-6.25q5.25 8.25 10.5 0l4 6.25");
}

</style>
