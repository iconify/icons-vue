<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq5agxnox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-monument" /></template>
<style>
.rq5agxnox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15.5v-8L12 3l3 4.5v8m-8 0h10a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 17A1.5 1.5 0 0 1 7 15.5m-2.5 3h15A1.5 1.5 0 0 1 21 20a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 20a1.5 1.5 0 0 1 1.5-1.5M9 7.5h6");
}

</style>
