<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i83jhkfyq"/><path class="yrjo2z0vf"/><path class="gsaz-_nbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:party-invitation" /></template>
<style>
.gsaz-_nbv {
  d: path("m14.75 16.25l3.5 2.5l3.5-2.5");
}

.i83jhkfyq {
  d: path("M15.082 12.734L11 5.25L3.5 19h8.438");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrjo2z0vf {
  d: path("M9.5 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.25 11.75h7v5.75h-7Z");
}

</style>
