<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ekggvtblj"/><path class="ova03jb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:token-counter" /></template>
<style>
.ekggvtblj {
  cx: 8.75px;
  cy: 12px;
  r: 6px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ova03jb8f {
  d: path("M6.25 9.5h5m-2.5 0V15M19 9.75v4.5M16.75 12h4.5");
}

</style>
