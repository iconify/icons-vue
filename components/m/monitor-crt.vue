<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipyx0wwka"/><path class="b69ftg09o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-crt" /></template>
<style>
.b69ftg09o {
  d: path("M10.5 6.5h3A3.5 3.5 0 0 1 17 10v1a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 11v-1a3.5 3.5 0 0 1 3.5-3.5M17 13h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipyx0wwka {
  d: path("M4 5c0-1.25 1-2 2-2h12c1 0 2 .75 2 2v10.5c0 2-1 3-2.5 3h-11c-1.5 0-2.5-1-2.5-3Zm3 16h10");
}

</style>
