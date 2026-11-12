<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG7VI6acno"><g class="k2u665ban"><circle class="b4dyhhbeb"/><path class="jngxrubhu"/></g></mask></defs><path mask="url(#SVG7VI6acno)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bug-line-duotone" /></template>
<style>
.b4dyhhbeb {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  stroke: var(--svg-color--gray, gray);
}

.jngxrubhu {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M11.5 15.5a3 3 0 0 1-3-3v-2m3 5a3 3 0 0 0 3-3v-2m-3 5v-5m3 0a3 3 0 1 0-6 0m6 0h-6m6.072 1H16m-9 0h1.5m6 2.5l1 .5m-7-.5l-1 .5m7-5.5l1-.5m-7 .5l-1-.5M20 20l2 2");
}

.k2u665ban {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w49j0rbvv {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
