<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvh59ofnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-customs" /></template>
<style>
.zvh59ofnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M5.75 12h12.5A1.75 1.75 0 0 1 20 13.75v1a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 14.75v-1A1.75 1.75 0 0 1 5.75 12m4.75-4.25V12m3-4.25V12M4 20h16");
}

</style>
