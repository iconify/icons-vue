<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6-3sub9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mask-medical" /></template>
<style>
.u6-3sub9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.25c3.5-1.5 7.5-1.5 11 0v7.5c-3.5 2-7.5 2-11 0ZM8.75 11h6.5m-6.5 3h6.5M6.5 9.25H5a2.25 2.25 0 0 0-2.25 2.25v.5a3 3 0 0 0 2.75 3h1m11-5.75H19a2.25 2.25 0 0 1 2.25 2.25v.5a3 3 0 0 1-2.75 3h-1");
}

</style>
