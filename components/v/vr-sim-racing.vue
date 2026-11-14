<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbgfeacvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-sim-racing" /></template>
<style>
.rbgfeacvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h15a2 2 0 0 1 2 2v6.25a2 2 0 0 1-2 2H15l-1.5-2.5h-3L9 13.25H4.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m11 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m0 0H21m-2.75 0v2.75");
}

</style>
