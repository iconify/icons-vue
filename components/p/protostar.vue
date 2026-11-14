<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w2k9-ubcr"/><path class="ssq-b4r1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:protostar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ssq-b4r1c {
  d: path("M2.5 12a9.5 3.25 0 1 0 19 0a9.5 3.25 0 1 0-19 0");
}

.w2k9-ubcr {
  d: path("m12.75 7l.599 2.795a1.5 1.5 0 0 0 .796 1.027l.855.428a.839.839 0 0 1 0 1.5l-.855.428a1.5 1.5 0 0 0-.796 1.027L12.75 17a.767.767 0 0 1-1.5 0l-.599-2.795a1.5 1.5 0 0 0-.796-1.027L9 12.75a.839.839 0 0 1 0-1.5l.855-.428a1.5 1.5 0 0 0 .796-1.027L11.25 7a.767.767 0 0 1 1.5 0");
}

</style>
