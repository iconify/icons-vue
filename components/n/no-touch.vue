<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="hp27us-gp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-touch" /></template>
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

.hp27us-gp {
  d: path("m8.75 14.75l-1.6-2.1a1 1 0 0 1 1.6-1.2v-2.2a1 1 0 0 1 2 0v-1a1 1 0 0 1 2 0v.25a1 1 0 0 1 2 0v1.25a1 1 0 0 1 2 0V14a4 4 0 0 1-4 4h-.5a3.5 3.5 0 0 1-3.5-3.25M5.5 5.5l13 13");
}

</style>
