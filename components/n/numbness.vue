<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pms_q0bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:numbness" /></template>
<style>
.pms_q0bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6v2.25m3-4.25v2.75m3-2v2.5m2.25 0v2M8.75 11v4.5m3-5.75V11m3-1v1M17 12v3.5q0 1.875-.75 3m-1.75 2.25c-.75.5-1.75.75-2.75.75s-1.75-.25-2.5-.75M7 19.25L5.5 17M4 14.75c-.5-1.25-.25-2.25.75-2.5c.5-.15 1 0 1.5.5");
}

</style>
