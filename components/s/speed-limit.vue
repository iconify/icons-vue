<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="fha1c8xwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speed-limit" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.fha1c8xwq {
  d: path("M6.75 8h3l-2 3a2.4 2.4 0 1 1-1.25 4.25M15 8a2.25 2.25 0 0 1 2.25 2.25v3.5a2.25 2.25 0 0 1-4.5 0v-3.5A2.25 2.25 0 0 1 15 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
