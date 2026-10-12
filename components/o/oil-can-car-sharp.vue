<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifbutlbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-can-car-sharp" /></template>
<style>
.ifbutlbmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h6.5l.71.71l.58.58l.71.71l.96-.29l4.58-1.42L21 11l-.63.77l-3.24 3.96l-.63.77v2.25H5V11zm2.75 0V8.75m-2 0h4M5 13H2.75v3.75H5m15-1l1.25 1.563v.937a1.25 1.25 0 0 1-2.5 0v-.937z");
}

</style>
