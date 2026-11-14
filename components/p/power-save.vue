<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzsgridhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:power-save" /></template>
<style>
.lzsgridhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 4.639A8.5 8.5 0 0 1 20.5 12M12 20.5A8.5 8.5 0 0 1 7.75 4.639M12 2.5V10m3 11c0-3.5 2-6 6-6c0 3.5-2 6-6 6");
}

</style>
