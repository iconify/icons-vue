<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-0226dgs"/><path class="a-_5ti-5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retired-number" /></template>
<style>
.a-_5ti-5e {
  d: path("M9.25 14.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0m0 4.25l5.5-8.5");
}

.a-0226dgs {
  d: path("m9.734 3.856l1.127 1.315a1.5 1.5 0 0 0 2.278 0l1.127-1.315a1.5 1.5 0 0 1 1.76-.39l3.775 1.716a1.5 1.5 0 0 1 .85 1.071l.578 2.891a1.5 1.5 0 0 1-1.059 1.736l-1.082.309A1.5 1.5 0 0 0 18 12.631V19.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19.5v-6.869a1.5 1.5 0 0 0-1.088-1.442L3.83 10.88a1.5 1.5 0 0 1-1.059-1.736l.578-2.891a1.5 1.5 0 0 1 .85-1.071l3.775-1.716a1.5 1.5 0 0 1 1.76.39M9 3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
