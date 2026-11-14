<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cjd8zwb6b"/><path class="aam547bxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:u-turn-left" /></template>
<style>
.aam547bxs {
  d: path("m4.5 13l3 3l3-3");
}

.cjd8zwb6b {
  d: path("M17.5 20V10a5 5 0 0 0-10 0v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
