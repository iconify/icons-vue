<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3cpd_bdv"/><path class="yf_xoo3cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-event" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3cpd_bdv {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M3 11c5 3 13 3 18 0");
}

.yf_xoo3cr {
  d: path("M5.75 12.25za1.37 1.37 0 0 1 .793 1.914l-.168.336a.753.753 0 0 1-1.399-.135l-.303-1.092A.841.841 0 0 1 5.75 12.25m4.5 1za1.155 1.155 0 0 1 .857 1.628l-.232.497a.782.782 0 0 1-1.459-.11l-.237-.806a.953.953 0 0 1 1.071-1.209m3.5 0za.953.953 0 0 1 1.071 1.209l-.237.806a.782.782 0 0 1-1.459.11l-.232-.497a1.155 1.155 0 0 1 .857-1.628m4.5-1za.841.841 0 0 1 1.077 1.023l-.303 1.092a.753.753 0 0 1-1.399.135l-.168-.336a1.37 1.37 0 0 1 .793-1.914M3 11v10.5M21 11v10.5");
}

</style>
