<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m13zn57lb"/><path class="ikd7ahxtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stakeholders" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ikd7ahxtr {
  d: path("M4 19.25h4.5a.75.75 0 0 0 .75-.75c0-2.9-1.35-5-3-5s-3 2.1-3 5a.75.75 0 0 0 .75.75m10.75-3.5v-3.5a3.5 3.5 0 1 0 3.5 3.5Zm3-3v-3.5a3.5 3.5 0 0 1 3.5 3.5Z");
}

.m13zn57lb {
  cx: 6.25px;
  cy: 8.5px;
  r: 2.5px;
}

</style>
