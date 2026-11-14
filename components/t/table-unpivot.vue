<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgk738b_v"/><path class="t0failb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-unpivot" /></template>
<style>
.cgk738b_v {
  d: path("M4.25 2.5h9.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-9.5A1.75 1.75 0 0 1 2.5 5.75v-1.5A1.75 1.75 0 0 1 4.25 2.5m14 8.5h1.5a1.75 1.75 0 0 1 1.75 1.75v7a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-7A1.75 1.75 0 0 1 18.25 11M6.75 2.5v5m4.5-5v5m5.25 7h5m-5 3.5h5M16 5h1.25A1.75 1.75 0 0 1 19 6.75v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0failb8o {
  d: path("M17.25 7.25L19 9l1.75-1.75");
}

</style>
