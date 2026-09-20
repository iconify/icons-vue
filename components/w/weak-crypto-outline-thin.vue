<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfs8wlfhn"/><path class="iml3cbclx"/><path class="gc47fwlhb"/><path class="fsz2pfyxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weak-crypto-outline-thin" /></template>
<style>
.fsz2pfyxd {
  d: path("m14.5 13 -5 5");
}

.gc47fwlhb {
  d: path("m9.5 13 5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iml3cbclx {
  d: path("M8 7a4 4 0 0 1 8 0");
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>
