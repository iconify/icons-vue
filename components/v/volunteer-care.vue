<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b00afka8g"/><path class="fip-uebtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volunteer-care" /></template>
<style>
.b00afka8g {
  d: path("M8 21.5V19l-3.25-4.75c-.75-1-.5-2 .25-2.5s1.75-.25 2.25.75L8.5 14V5.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5V11V4c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5v7v-5.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5v6V8c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5v7c0 3-2 4.5-3.5 4.5v2");
}

.fip-uebtl {
  fill: currentColor;
  d: path("M14.25 17.25s-2.75-1.75-2.75-3.5c0-.75.75-1.5 1.5-1.5c.5 0 1 .5 1.25.75c.25-.25.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.5c0 1.75-2.75 3.5-2.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
