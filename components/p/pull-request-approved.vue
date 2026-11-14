<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="op1a7pp5n"/><path class="zi3l0qb3p"/><path class="jw809gbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-request-approved" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jw809gbmr {
  d: path("m13 3l-2 2l2 2m1.75 11l2 2L21 15.75");
}

.op1a7pp5n {
  d: path("M3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 7.25v9.5M3.75 19a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11.5-8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.zi3l0qb3p {
  d: path("M17.5 8.25V5H11");
}

</style>
