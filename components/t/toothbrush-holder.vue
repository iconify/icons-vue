<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnc5nibvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toothbrush-holder" /></template>
<style>
.mnc5nibvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 10l1 10c.1 1 .5 1.5 1.5 1.5h7c1 0 1.4-.5 1.5-1.5l1-10m-5-1v9.5m0-16za1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 13 9a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 13 2.5M8.5 4h2.75M8.5 7h2.75");
}

</style>
