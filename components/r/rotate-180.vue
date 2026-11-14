<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gx7jiib5h"/><path class="tl51n0-xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rotate-180" /></template>
<style>
.gx7jiib5h {
  d: path("M3.5 15.5a8 8 0 0 1 16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tl51n0-xo {
  d: path("m17 13l2.5 2.5L22 13m-10.5 2.5h.01");
}

</style>
