<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8a_h-_5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-ultrawide" /></template>
<style>
.g8a_h-_5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.938 6h12.125A3.94 3.94 0 0 1 22 9.938v1.625a3.94 3.94 0 0 1-3.937 3.937H5.938A3.94 3.94 0 0 1 2 11.563V9.938A3.94 3.94 0 0 1 5.938 6M12 15.5V19m-3.5 0h7");
}

</style>
