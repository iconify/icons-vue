<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xjot2i5mc"/><path class="umtymsyts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spear-phishing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umtymsyts {
  d: path("M2.75 5.75L12 11.5l9.25-5.75M12 11.5v3.25a2.25 2.25 0 0 1-4.5 0v-1.5");
}

.xjot2i5mc {
  width: 18.5px;
  height: 16px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
