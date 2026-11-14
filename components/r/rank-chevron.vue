<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w59o4cb6g"/><path class="ddos-4grn"/><path class="c0d6mccdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rank-chevron" /></template>
<style>
.c0d6mccdx {
  d: path("m5 20.5l7-7l7 7");
}

.ddos-4grn {
  d: path("m5 15.5l7-7l7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w59o4cb6g {
  d: path("m5 10.5l7-7l7 7");
}

</style>
