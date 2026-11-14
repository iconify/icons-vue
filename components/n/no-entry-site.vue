<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8pd54bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-entry-site" /></template>
<style>
.v8pd54bcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h13.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 17.75 10H4.25A1.75 1.75 0 0 1 2.5 8.25v-3A1.75 1.75 0 0 1 4.25 3.5M5.5 10v10.5M16 10v1.7M9 10l3-6.5m.75 6.5l3-6.5M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m1.25 2.5l5-5");
}

</style>
