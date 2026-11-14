<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwdyqlgjv"/><path class="lhh_-bb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhh_-bb3u {
  d: path("m9.186 15.979l3.498 1.166a1.283 1.283 0 0 1-.184 2.48l-3.402.595a1.5 1.5 0 0 1-1.752-1.335l-.128-1.341a1.5 1.5 0 0 1 1.968-1.565m5.064-1.229l3.25 4");
}

.lwdyqlgjv {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
