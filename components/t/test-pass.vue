<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crlzg-bus"/><path class="kin_ijb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-pass" /></template>
<style>
.crlzg-bus {
  d: path("M11 2.75h2q1.25 0 1.25 1.25v3.5q0 1.25.56 2.37l5.13 10.26q.56 1.12-.69 1.12H4.75q-1.25 0-.69-1.12L9.19 9.87q.56-1.12.56-2.37V4q0-1.25 1.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kin_ijb6z {
  d: path("m9.25 16.25l2 2l3.75-4");
}

</style>
