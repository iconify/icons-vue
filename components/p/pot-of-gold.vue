<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ke-i0wiar"/><path class="c02gm5bep"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pot-of-gold" /></template>
<style>
.c02gm5bep {
  d: path("M7.25 6.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m-3 3.25a2.5 2.5 0 0 1 3-3.25m9.5 3.25a2.5 2.5 0 0 0-3-3.25M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ke-i0wiar {
  d: path("M4.375 9.5h12.25A1.375 1.375 0 0 1 18 10.875a1.375 1.375 0 0 1-1.375 1.375H4.375A1.375 1.375 0 0 1 3 10.875A1.375 1.375 0 0 1 4.375 9.5m.125 2.75c-.75 4.25 1 8.25 6 8.25q.624 0 1.182-.081");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
