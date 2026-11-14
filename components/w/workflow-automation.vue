<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uctec_b2g"/><path class="rojdpxb8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workflow-automation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rojdpxb8k {
  d: path("m9.75 15.25l2 2l-2 2m7.625-15.204l-2.066 2.842A.7.7 0 0 0 15.875 8a1.01 1.01 0 0 1 .965 1.312l-.215.688a.383.383 0 0 0 .666.35l2.362-3.017a.67.67 0 0 0-.528-1.083a1.127 1.127 0 0 1-1.105-1.348l.105-.527a.419.419 0 0 0-.75-.329");
}

.uctec_b2g {
  d: path("M5.625 3.5h1.25A2.625 2.625 0 0 1 9.5 6.125v1.25A2.625 2.625 0 0 1 6.875 10h-1.25A2.625 2.625 0 0 1 3 7.375v-1.25A2.625 2.625 0 0 1 5.625 3.5m11.5 10.5h1.25A2.625 2.625 0 0 1 21 16.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.25A2.625 2.625 0 0 1 17.125 14M6.25 10v5.25a2 2 0 0 0 2 2h3.25");
}

</style>
