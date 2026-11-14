<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vss8_u8ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:room-dimensions" /></template>
<style>
.vss8_u8ev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H11V9h10.5v7.5h-19zm0 17.5h19m-19-1.5v3m19-3v3m-17-2.75L2.5 20l2 1.25m15-2.5l2 1.25l-2 1.25");
}

</style>
