<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfi034_tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:network-lan" /></template>
<style>
.pfi034_tz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h2.75A2.625 2.625 0 0 1 10.5 5.625v1.25A2.625 2.625 0 0 1 7.875 9.5h-2.75A2.625 2.625 0 0 1 2.5 6.875v-1.25A2.625 2.625 0 0 1 5.125 3m11 0h2.75A2.625 2.625 0 0 1 21.5 5.625v1.25A2.625 2.625 0 0 1 18.875 9.5h-2.75A2.625 2.625 0 0 1 13.5 6.875v-1.25A2.625 2.625 0 0 1 16.125 3M10.75 17h2.5A1.75 1.75 0 0 1 15 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 19.75v-1A1.75 1.75 0 0 1 10.75 17M6.5 9.5v3h11v-3m-5.5 3V17");
}

</style>
