<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lof8p1b2q"/><path class="jbxk5vbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:voltmeter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbxk5vbrc {
  d: path("M10.5 13.25L12 16l1.5-2.75");
}

.lof8p1b2q {
  d: path("M4 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0M9 18l-2 3.5m8-3.5l2 3.5m-5-10.75L8.5 6");
}

</style>
