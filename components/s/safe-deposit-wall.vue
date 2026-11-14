<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cv27csblk"/><path class="eu2288bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safe-deposit-wall" /></template>
<style>
.cv27csblk {
  d: path("M5.125 3h9.25A2.625 2.625 0 0 1 17 5.625v12.75A2.625 2.625 0 0 1 14.375 21h-9.25A2.625 2.625 0 0 1 2.5 18.375V5.625A2.625 2.625 0 0 1 5.125 3");
}

.eu2288bmh {
  d: path("m19.044 3.795l1.5.583a1.5 1.5 0 0 1 .956 1.398v2.781a1.5 1.5 0 0 1-2.044 1.398l-1.5-.583A1.5 1.5 0 0 1 17 7.974V5.193a1.5 1.5 0 0 1 2.044-1.398M9.75 3v18M2.5 9H17M2.5 15H17M6.25 6h.01m-.01 6h.01m7.24 0h.01m-7.26 6h.01m7.24 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
