<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn3r7kbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-smoking" /></template>
<style>
.sn3r7kbnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h6.81m6.38 0H21v3.5h-1.31m-6.38 0H3V13m14.5 0v1.32M3.75 3.75l16.5 16.5");
}

</style>
