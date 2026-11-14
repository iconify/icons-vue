<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggo9l_7_u"/><path class="jeffvdsrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:van-de-graaff" /></template>
<style>
.ggo9l_7_u {
  d: path("M3 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jeffvdsrc {
  d: path("M8.5 13za1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 7 20v-5.5A1.5 1.5 0 0 1 8.5 13m-5 8.5h10m3-4a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3-7.5l3 2l-1.5 1.25L18 15");
}

</style>
