<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mkksvcbdq"/><path class="uyiddkvas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sun-lounger" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkksvcbdq {
  cx: 7px;
  cy: 7.5px;
  r: 2.75px;
}

.uyiddkvas {
  d: path("M2.75 15.25h12l3.75-5.5m-13.25 5.5v4.5m9.5-4.5v4.5");
}

</style>
