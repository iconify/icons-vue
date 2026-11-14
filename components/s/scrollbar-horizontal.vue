<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gz994lbcl"/><path class="ji82kcb9n"/><path class="appg_y4mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scrollbar-horizontal" /></template>
<style>
.appg_y4mg {
  fill: currentColor;
  d: path("M11 10.75h2A1.25 1.25 0 0 1 14.25 12A1.25 1.25 0 0 1 13 13.25h-2A1.25 1.25 0 0 1 9.75 12A1.25 1.25 0 0 1 11 10.75");
}

.gz994lbcl {
  d: path("M6.375 7h11.25A4.375 4.375 0 0 1 22 11.375v1.25A4.375 4.375 0 0 1 17.625 17H6.375A4.375 4.375 0 0 1 2 12.625v-1.25A4.375 4.375 0 0 1 6.375 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji82kcb9n {
  d: path("M7 9.75L4.75 12L7 14.25m10-4.5L19.25 12L17 14.25");
}

</style>
