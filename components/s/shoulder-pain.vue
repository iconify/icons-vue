<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwdyqlgjv"/><path class="jrhp6xbex"/><path class="drq1kjbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoulder-pain" /></template>
<style>
.drq1kjbes {
  d: path("m18.5 11.75l1.5-2m.5 4.25l1.5-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrhp6xbex {
  fill: currentColor;
  d: path("M16.739 16.173za.62.62 0 0 0 .707.292a.275.275 0 0 1 .339.339a.62.62 0 0 0 .292.707a.275.275 0 0 1 0 .478a.62.62 0 0 0-.292.707a.275.275 0 0 1-.339.339a.62.62 0 0 0-.707.292a.275.275 0 0 1-.478 0a.62.62 0 0 0-.707-.292a.275.275 0 0 1-.339-.339a.62.62 0 0 0-.292-.707a.275.275 0 0 1 0-.478a.62.62 0 0 0 .292-.707a.275.275 0 0 1 .339-.339a.62.62 0 0 0 .707-.292a.275.275 0 0 1 .478 0");
}

.lwdyqlgjv {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
