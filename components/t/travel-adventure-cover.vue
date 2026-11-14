<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxe06zomx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-adventure-cover" /></template>
<style>
.vxe06zomx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20L9 9l4 6l3-4l5.5 9ZM9 9V4.5m1.193.373l.807.252a.655.655 0 0 1 0 1.25l-.807.252A.92.92 0 0 1 9 5.75a.92.92 0 0 1 1.193-.877");
}

</style>
