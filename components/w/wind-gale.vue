<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsns9rzhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wind-gale" /></template>
<style>
.nsns9rzhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14 20l2.5-9M14 9a3.25 5 0 1 0 6.5 0A3.25 5 0 1 0 14 9M2.5 20h19M2.5 6.5H11M2.5 11h7");
}

</style>
