<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wu7lmw6mt"/><path class="hzb3j89ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:token-limit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzb3j89ql {
  fill: currentColor;
  d: path("M7.5 10.75H16A1.25 1.25 0 0 1 17.25 12A1.25 1.25 0 0 1 16 13.25H7.5A1.25 1.25 0 0 1 6.25 12a1.25 1.25 0 0 1 1.25-1.25");
}

.wu7lmw6mt {
  d: path("M20 8H6a2.5 2.5 0 0 0-2.5 2.5v3A2.5 2.5 0 0 0 6 16h14m0-11.5v15");
}

</style>
