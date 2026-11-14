<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr6grkbdu"/><path class="i4sm4fkgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:title-insurance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4sm4fkgl {
  d: path("M9.125 7h5.75A1.125 1.125 0 0 1 16 8.125a1.125 1.125 0 0 1-1.125 1.125h-5.75A1.125 1.125 0 0 1 8 8.125A1.125 1.125 0 0 1 9.125 7M9 9.25V14m6-4.75V14m-5.875 0h5.75A1.125 1.125 0 0 1 16 15.125a1.125 1.125 0 0 1-1.125 1.125h-5.75A1.125 1.125 0 0 1 8 15.125A1.125 1.125 0 0 1 9.125 14");
}

.kr6grkbdu {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5.5Z");
}

</style>
