<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vo-9m7b2x"/><circle class="c12c3kbgx"/><circle class="nopx6ibuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moped" /></template>
<style>
.c12c3kbgx {
  cx: 5.25px;
  cy: 18px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nopx6ibuz {
  cx: 18.75px;
  cy: 18px;
  r: 2.5px;
}

.vo-9m7b2x {
  d: path("M9.5 8.25h2.75q.75 0 .6.74l-.2 1.02q-.15.74-.9.74h-1.5q-.75 0-.97-.72l-.31-1.06q-.22-.72.53-.72M7.75 18H11c2.5 0 3.5-5.5 5.56-7.5m-5.56.25v10m7.05-5.15L14.96 5h-2.21");
}

</style>
