<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e837ahb1c"/><path class="m_oz_zbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:walkie-talkie" /></template>
<style>
.e837ahb1c {
  width: 10.5px;
  height: 13.5px;
  x: 6.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_oz_zbvp {
  d: path("M9.5 7.25v-4.5m5 4.5v-1.5M9.75 11h4.5m-4.5 2.5h4.5M9.75 16h4.5");
}

</style>
