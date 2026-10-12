<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="kv-qovpzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-phones" /></template>
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

.kv-qovpzt {
  d: path("M10.25 6.5h3.5a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1m1.25 9h1m-7-10l13 13");
}

</style>
