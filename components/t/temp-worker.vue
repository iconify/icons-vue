<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayy-trbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:temp-worker" /></template>
<style>
.ayy-trbnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5L10.5 9M18 2.5L13.5 9m-4.375 2h5.75a2.625 2.625 0 0 1 2.625 2.625v5.25a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 18.875v-5.25A2.625 2.625 0 0 1 9.125 11m2.625-2.5h.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 12.25 11h-.5a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25M10 13.75h4m-4 5h4m-3.25-5l2.5 5m0-5l-2.5 5");
}

</style>
