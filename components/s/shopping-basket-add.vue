<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf6hyhuda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shopping-basket-add" /></template>
<style>
.rf6hyhuda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.645 9.5h14.457a1.166 1.166 0 0 1 1.148 1.375a1.675 1.675 0 0 1-1.648 1.375h-4.727a2.625 2.625 0 0 0-2.625 2.625v3A2.625 2.625 0 0 1 9.625 20.5H6.691a2.625 2.625 0 0 1-2.583-2.155l-1.045-5.75A2.625 2.625 0 0 1 5.645 9.5M7 9.5l3-6m7 6l-3-6M8 13v4m10-2v6m-3-3h6");
}

</style>
