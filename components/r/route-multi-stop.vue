<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdpatccng"/><path class="dsskuqc0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-multi-stop" /></template>
<style>
.dsskuqc0o {
  fill: currentColor;
  d: path("M17.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdpatccng {
  d: path("M2 19.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0h7.7m4.8-4.8V7M17 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
