<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrt6xuaps"/><path class="ujny1bbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:one-way" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujny1bbix {
  d: path("M14.5 5.75L16.75 8l-2.25 2.25");
}

.wrt6xuaps {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 13H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 3m6 10v8M6.5 8h10.25");
}

</style>
