<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a--t5ztqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:support-dashboard" /></template>
<style>
.a--t5ztqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h2.75A2.625 2.625 0 0 1 10.5 5.125v5.25A2.625 2.625 0 0 1 7.875 13h-2.75A2.625 2.625 0 0 1 2.5 10.375v-5.25A2.625 2.625 0 0 1 5.125 2.5m0 13.5h2.75a2.625 2.625 0 0 1 2.625 2.625v.25A2.625 2.625 0 0 1 7.875 21.5h-2.75A2.625 2.625 0 0 1 2.5 18.875v-.25A2.625 2.625 0 0 1 5.125 16m11-13.5h2.75A2.625 2.625 0 0 1 21.5 5.125v2.25A2.625 2.625 0 0 1 18.875 10h-2.75A2.625 2.625 0 0 1 13.5 7.375v-2.25A2.625 2.625 0 0 1 16.125 2.5M14.5 18a3.25 3.25 0 0 1 6.5 0m-6.5 0za1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19a1 1 0 0 1 1-1m6.5 0za1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19a1 1 0 0 1 1-1");
}

</style>
