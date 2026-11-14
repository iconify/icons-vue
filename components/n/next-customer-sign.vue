<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxnej2b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:next-customer-sign" /></template>
<style>
.sxnej2b6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 12.25l.568-.994A1.5 1.5 0 0 1 6.37 10.5h11.26a1.5 1.5 0 0 1 1.302.756l.568.994A1.17 1.17 0 0 1 18.484 14H5.516A1.17 1.17 0 0 1 4.5 12.25M5.25 14h13.5a2.75 2.75 0 0 1 2.75 2.75a2.75 2.75 0 0 1-2.75 2.75H5.25a2.75 2.75 0 0 1-2.75-2.75A2.75 2.75 0 0 1 5.25 14m.25-3.5l1 3.5m-1.25 2.75h.01m13.49 0h.01");
}

</style>
