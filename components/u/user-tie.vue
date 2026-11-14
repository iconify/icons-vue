<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n3w-ydb0b"/><path class="ln-u-l4lh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-tie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln-u-l4lh {
  d: path("m12.625 15.25l.102.122a1.5 1.5 0 0 1 .279 1.408L12.625 18a.655.655 0 0 1-1.25 0l-.381-1.22a1.5 1.5 0 0 1 .279-1.408l.102-.122a.814.814 0 0 1 1.25 0");
}

.n3w-ydb0b {
  d: path("M4 20c0-3.3 3.6-5.5 8-5.5s8 2.2 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
