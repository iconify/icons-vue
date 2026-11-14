<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="efmla-bac"/><path class="afj7z08zv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safe-deposit-box" /></template>
<style>
.afj7z08zv {
  d: path("M7 6.5h2A1.5 1.5 0 0 1 10.5 8A1.5 1.5 0 0 1 9 9.5H7A1.5 1.5 0 0 1 5.5 8A1.5 1.5 0 0 1 7 6.5m8 0h2A1.5 1.5 0 0 1 18.5 8A1.5 1.5 0 0 1 17 9.5h-2A1.5 1.5 0 0 1 13.5 8A1.5 1.5 0 0 1 15 6.5m-8 5h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 14.5H7A1.5 1.5 0 0 1 5.5 13A1.5 1.5 0 0 1 7 11.5m8 0h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m-8 5h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 19.5H7A1.5 1.5 0 0 1 5.5 18A1.5 1.5 0 0 1 7 16.5m8 0h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.efmla-bac {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5v9a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16.5v-9A3.5 3.5 0 0 1 6.5 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
