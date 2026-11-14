<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idtyp8ffs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moonset" /></template>
<style>
.idtyp8ffs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 16A7 7 0 0 1 13.5 5a6 6 0 0 0-3.25 11M2.5 16h10.25M18 14.5v7m-3-3l3 3l3-3");
}

</style>
