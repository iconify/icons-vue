<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o61rqne9e"/><path class="iax1i0b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reagent-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iax1i0b6h {
  d: path("m13.099 12.684l1.203 1.295a1.5 1.5 0 0 1 0 2.042l-1.203 1.295a1.5 1.5 0 0 1-2.198 0l-1.203-1.295a1.5 1.5 0 0 1 0-2.042l1.203-1.295a1.5 1.5 0 0 1 2.198 0");
}

.o61rqne9e {
  d: path("M9.5 5.75V8.5H7c-1.1 0-2 .9-2 2v9c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-9c0-1.1-.9-2-2-2h-2.5V5.75M10.125 2.5h3.75A1.625 1.625 0 0 1 15.5 4.125a1.625 1.625 0 0 1-1.625 1.625h-3.75A1.625 1.625 0 0 1 8.5 4.125A1.625 1.625 0 0 1 10.125 2.5");
}

</style>
