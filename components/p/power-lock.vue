<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjs5bqbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-lock" /></template>
<style>
.jjs5bqbbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 4.639A8.5 8.5 0 0 1 20.5 12M12 20.5A8.5 8.5 0 0 1 7.75 4.639M12 2.5V10m3 7.75h6v3.75h-6Zm1.5 0V16.5a1.5 1.5 0 0 1 3 0v1.25");
}

</style>
