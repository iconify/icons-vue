<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t68qcrbio"/><path class="bo9l5xzrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nosql-document" /></template>
<style>
.bo9l5xzrv {
  d: path("M10 8.5c-1 0-1.25.5-1.25 1.25V11c0 .5-.5 1-1.25 1c.75 0 1.25.5 1.25 1v1.25C8.75 15 9 15.5 10 15.5m4-7c1 0 1.25.5 1.25 1.25V11c0 .5.5 1 1.25 1c-.75 0-1.25.5-1.25 1v1.25c0 .75-.25 1.25-1.25 1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t68qcrbio {
  d: path("M4.5 10A7.5 7.5 0 0 1 12 2.5h7.5V14a7.5 7.5 0 0 1-7.5 7.5H4.5Z");
}

</style>
