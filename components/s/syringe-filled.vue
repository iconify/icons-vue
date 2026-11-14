<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfoos5b7g"/><path class="f4ductbwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:syringe-filled" /></template>
<style>
.bfoos5b7g {
  d: path("m15.359 6.873l1.768 1.768a1.75 1.75 0 0 1 0 2.475l-4.95 4.95a1.75 1.75 0 0 1-2.475 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.475l4.95-4.95a1.75 1.75 0 0 1 2.475 0m-2.298-2.298l6.364 6.364m-.707-5.657l-2.475 2.475m1.06-3.889l2.829 2.829M8.818 15.182l-3.536 3.536");
}

.f4ductbwl {
  fill: currentColor;
  d: path("M14.475 9.525za1.25 1.25 0 0 1 0 1.768l-2.652 2.652a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l2.652-2.652a1.25 1.25 0 0 1 1.768 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
