<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l365jbciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roof-rack" /></template>
<style>
.l365jbciz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.25v-4l3-1l2-4h9l2 4l3 1v4h-2a2.5 2.5 0 0 0-5 0h-5a2.5 2.5 0 0 0-5 0Zm5.5-9v-3.5m8 3.5v-3.5m-10.5 0h5m3 0h5");
}

</style>
