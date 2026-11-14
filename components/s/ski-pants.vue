<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe6674yyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-pants" /></template>
<style>
.qe6674yyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h12l1.5 13.5H14L12 13l-2 8.5H4.5Zm1.5 0l1-5.5m8 5.5l-1-5.5m-10.75 16h6m2.5 0h6");
}

</style>
