<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa2891bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:side-mirror" /></template>
<style>
.sa2891bab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v18m0-7h5m0-6c0-1.5 1-2.5 2.5-2.5h8A2.5 2.5 0 0 1 21.5 8v4.5c0 3-2.5 5-6 5H11A2.5 2.5 0 0 1 8.5 15Zm4 5.5l4-4");
}

</style>
