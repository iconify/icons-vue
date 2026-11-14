<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0eo5bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sliding-gate" /></template>
<style>
.aq0eo5bsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V4m19 17.5V4m-19 15h19M7.25 9.25h5.5A1.75 1.75 0 0 1 14.5 11v6.25A1.75 1.75 0 0 1 12.75 19h-5.5a1.75 1.75 0 0 1-1.75-1.75V11a1.75 1.75 0 0 1 1.75-1.75M8 4.5h8m-2-2l2 2l-2 2");
}

</style>
