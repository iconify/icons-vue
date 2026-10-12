<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj6s_imki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-goggles" /></template>
<style>
.uj6s_imki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5h10a2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-2.5 2.5h-2.5q-2.5-2.25-5 0H7A2.5 2.5 0 0 1 4.5 13v-2A2.5 2.5 0 0 1 7 8.5m3 0v2.25m4-2.25v2.25M2.75 12H4.5m15 0h1.75");
}

</style>
