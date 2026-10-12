<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrvo6fcox"/><path class="z--jk5bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triage-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrvo6fcox {
  d: path("M10.5 2.75h3q1.5 0 2.56 1.06l1.13 1.13Q18.25 6 18.25 7.5v12.25q0 1.5-1.5 1.5h-9.5q-1.5 0-1.5-1.5V7.5q0-1.5 1.06-2.56l1.13-1.13Q9 2.75 10.5 2.75");
}

.z--jk5bnq {
  d: path("M13 6.5a1 1 0 1 1-2 0a1 1 0 1 1 2 0m-4.5 3.75h7M8.5 15h7m-7 3h7");
}

</style>
