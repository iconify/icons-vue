<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="erf249gnv"/><path class="asz7e_bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parka" /></template>
<style>
.asz7e_bcp {
  d: path("M6.5 7.75C6 5 7.25 3.5 9 3.75q1.5-1.125 3 0q1.5-1.125 3 0c1.75-.25 3 1.25 2.5 4m-11.25 4v9.5m11.5-9.5v9.5M6.25 14.5h11.5M6.25 18h11.5");
}

.erf249gnv {
  d: path("M9.75 6.75h4.5q1.25 0 2.41.48l1.93.79q1.16.48 1.32 1.72l1.18 9.27q.16 1.24-1.04 1.58l-1.1.32q-1.2.34-2.45.34h-9q-1.25 0-2.45-.34l-1.1-.32q-1.2-.34-1.04-1.58l1.18-9.27q.16-1.24 1.32-1.72l1.93-.79q1.16-.48 2.41-.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
