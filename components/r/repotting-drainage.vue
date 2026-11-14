<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbs1anbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repotting-drainage" /></template>
<style>
.qbs1anbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.119 2.5h11.762A1.75 1.75 0 0 1 19.6 4.58l-1.827 9.5a1.75 1.75 0 0 1-1.719 1.42H7.946a1.75 1.75 0 0 1-1.719-1.42L4.4 4.58A1.75 1.75 0 0 1 6.119 2.5m-1.369 4h14.5M8.5 18.5v3m3.5-3v3m3.5-3v3");
}

</style>
