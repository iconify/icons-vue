<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5al68qzw"/><path class="daa7eab3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:work-permit" /></template>
<style>
.daa7eab3q {
  d: path("M10.5 17.75a1.5 3.75 0 1 0 3 0a1.5 3.75 0 1 0-3 0m-2.25 0h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5al68qzw {
  d: path("M12 2.5za2 2 0 0 1 2 2v2a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m-5.25 6h10.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 17.25 11H6.75A1.25 1.25 0 0 1 5.5 9.75A1.25 1.25 0 0 1 6.75 8.5m1.5 9.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
