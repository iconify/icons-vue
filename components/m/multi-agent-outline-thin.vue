<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="arm3v4biy"/><path class="wxv870p2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-agent-outline-thin" /></template>
<style>
.arm3v4biy {
  d: path("M9.9 3.92a4.5 4.5 0 1 1 -3.8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxv870p2c {
  d: path("M17.9 11.92a4.5 4.5 0 1 1 -3.8 0");
}

</style>
