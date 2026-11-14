<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s52uzybxk"/><path class="tag7x2b-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mud-brick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s52uzybxk {
  d: path("M2.5 11L6 7.5h15.5V14L18 17.5H2.5Z");
}

.tag7x2b-n {
  d: path("M2.5 11H18v6.5m0-6.5l3.5-3.5M6 14.25h3.5");
}

</style>
