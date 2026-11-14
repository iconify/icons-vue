<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hu3v_abqu"/><path class="vy0pcpbej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toggle-disabled" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hu3v_abqu {
  d: path("M8 17.5a5.5 5.5 0 0 1 0-11m8 0a5.5 5.5 0 0 1 0 11m-5.5-11h3m-3 11h3");
}

.vy0pcpbej {
  d: path("M5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
