<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie17njorw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retention-rate" /></template>
<style>
.ie17njorw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m1.75 1.75V20.5m-3-11h6m-7 6c0 3 2 5 4 5s4-2 4-5M3.25 9a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M2.5 19.5c0-3 1.5-5 3.5-5s3.5 2 3.5 5Z");
}

</style>
