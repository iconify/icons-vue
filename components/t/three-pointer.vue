<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvb-z3lhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:three-pointer" /></template>
<style>
.dvb-z3lhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3v11M9 11h11.5M10 11l1.5 9.5h5L18 11M3.5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
