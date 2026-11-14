<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqdm1fbpy"/><path class="prus7zzno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oven-open" /></template>
<style>
.fqdm1fbpy {
  d: path("M7 3h10a3.5 3.5 0 0 1 3.5 3.5V14a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 14V6.5A3.5 3.5 0 0 1 7 3M4.581 17.5h14.838a1.5 1.5 0 0 1 1.423 1.026L21 19a1.14 1.14 0 0 1-1.081 1.5H4.081A1.14 1.14 0 0 1 3 19l.158-.474A1.5 1.5 0 0 1 4.581 17.5M3.5 8.5h17M7.25 5.75h.01m2.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prus7zzno {
  d: path("M8.625 11.5h6.75A1.625 1.625 0 0 1 17 13.125a1.625 1.625 0 0 1-1.625 1.625h-6.75A1.625 1.625 0 0 1 7 13.125A1.625 1.625 0 0 1 8.625 11.5");
}

</style>
