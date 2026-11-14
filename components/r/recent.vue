<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vyt9i_-zs"/><path class="ofy07xbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofy07xbzb {
  d: path("M6 3v3h3m3 1.5V12l3 2");
}

.vyt9i_-zs {
  d: path("M3.5 12A8.5 8.5 0 1 0 6 6");
}

</style>
