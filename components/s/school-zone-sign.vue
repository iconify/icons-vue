<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsenx9i9i"/><path class="fd94pubzi"/><path class="w06mib35b"/><path class="cxk84qbfq"/><path class="xxuifs61r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:school-zone-sign" /></template>
<style>
.cxk84qbfq {
  fill: currentColor;
  d: path("M14.5 14.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.dsenx9i9i {
  d: path("m14.308 7.261l5.343 9.864A2.625 2.625 0 0 1 17.343 21H6.657a2.625 2.625 0 0 1-2.308-3.875l5.343-9.864a2.625 2.625 0 0 1 4.616 0");
}

.fd94pubzi {
  fill: currentColor;
  d: path("M8.5 12.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w06mib35b {
  d: path("m7.75 18.25l2-3.5l2 3.5");
}

.xxuifs61r {
  d: path("m14.25 18.25l1.25-1.75l1.25 1.75");
}

</style>
