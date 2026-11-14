<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm5ldxddk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ribbon" /></template>
<style>
.xm5ldxddk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21L14 9c1-1.6.5-3.5-1-4.5c-.75-.5-1.25-.5-2 0c-1.5 1-2 2.9-1 4.5l7.5 12");
}

</style>
