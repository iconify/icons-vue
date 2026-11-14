<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-p71qb2c"/><path class="oj0jdlbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-filter-aid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-p71qb2c {
  d: path("M8.356 2.5h7.288a1.5 1.5 0 0 1 1.013 2.606l-2.671 2.448A1.5 1.5 0 0 0 13.5 8.66v.09a.75.75 0 0 1-.75.75h-1.5a.75.75 0 0 1-.75-.75v-.09a1.5 1.5 0 0 0-.486-1.106L7.343 5.106A1.5 1.5 0 0 1 8.356 2.5M5 13l1.5 8.5h11L19 13");
}

.oj0jdlbua {
  d: path("m12 12.25l1.75 3.25a2 2 0 1 1-3.5 0Z");
}

</style>
