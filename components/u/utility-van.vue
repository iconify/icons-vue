<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wby573kfx"/><path class="pxm23hbns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:utility-van" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxm23hbns {
  d: path("M4.5 17a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.125-8.5h.164a1.5 1.5 0 0 1 1.161.55l.675.825a.842.842 0 0 1-.652 1.375h-.848A1.375 1.375 0 0 1 12.5 9.875v-.5a.875.875 0 0 1 .875-.875");
}

.wby573kfx {
  d: path("M4.5 16.5h-2V7A1.5 1.5 0 0 1 4 5.5h11.5l4 5h.5a1.5 1.5 0 0 1 1.5 1.5v4.5h-2m-10 0h5");
}

</style>
