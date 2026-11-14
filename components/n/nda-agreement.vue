<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wg5qb1hmy"/><path class="vt-ei93zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nda-agreement" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vt-ei93zc {
  d: path("M17.75 12zA1.25 1.25 0 0 1 19 13.25V14a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 16.5 14v-.75A1.25 1.25 0 0 1 17.75 12");
}

.wg5qb1hmy {
  d: path("M2.5 12c3-4.5 7-5 9.5-3.5c2.5-1.5 6.5-1 9.5 3.5c-3 4.5-7 5.5-9.5 5.5s-6.5-1-9.5-5.5m2 0h15M7 11v2m2.5-2v2m2.5-2v2m2.5-2v2");
}

</style>
