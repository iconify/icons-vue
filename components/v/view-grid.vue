<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbd1p2brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:view-grid" /></template>
<style>
.mbd1p2brq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 3.5h1.75A2.625 2.625 0 0 1 10.5 6.125v1.75A2.625 2.625 0 0 1 7.875 10.5h-1.75A2.625 2.625 0 0 1 3.5 7.875v-1.75A2.625 2.625 0 0 1 6.125 3.5m10 0h1.75A2.625 2.625 0 0 1 20.5 6.125v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 13.5 7.875v-1.75A2.625 2.625 0 0 1 16.125 3.5m-10 10h1.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 7.875 20.5h-1.75A2.625 2.625 0 0 1 3.5 17.875v-1.75A2.625 2.625 0 0 1 6.125 13.5m10 0h1.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.75a2.625 2.625 0 0 1-2.625-2.625v-1.75a2.625 2.625 0 0 1 2.625-2.625");
}

</style>
