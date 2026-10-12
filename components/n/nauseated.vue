<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="t4651m81p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nauseated" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4651m81p {
  d: path("M7.5 8.25L10 9m6.5-.75L14 9m-6.25 2h2.5m3.5 0h2.5M8 16.25c.7-.9 1.3-.9 2 0s1.3.9 2 0s1.3-.9 2 0s1.3.9 2 0");
}

</style>
