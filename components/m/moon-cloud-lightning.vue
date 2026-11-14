<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piq4eiblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moon-cloud-lightning" /></template>
<style>
.piq4eiblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16.5h9a3 3 0 0 0 0-6a4.5 4.5 0 0 0-8.5 1a2.5 2.5 0 0 0-.5 5m14-13.75a3 3 0 1 0 1.75 3.75a2.25 2.25 0 0 1-1.75-3.75M11 16.5l-2 2.75h3L10 22");
}

</style>
