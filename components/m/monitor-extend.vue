<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nai_txbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-extend" /></template>
<style>
.nai_txbjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h5a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 11 15H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 5m11.125 3h1.75a2.625 2.625 0 0 1 2.625 2.625v3.75A2.625 2.625 0 0 1 18.875 17h-1.75a2.625 2.625 0 0 1-2.625-2.625v-3.75A2.625 2.625 0 0 1 17.125 8M8.5 15v3.5m-3 0h6m1-7.5H17");
}

</style>
