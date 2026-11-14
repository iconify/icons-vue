<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t171rpktc"/><path class="l9nvgdcnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:music-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9nvgdcnq {
  d: path("M19.245 15.331q-.008-.123-.026-.245q-.019-.121-.048-.241q-.029-.119-.069-.236t-.09-.229t-.11-.22q-.06-.107-.13-.209q-.069-.102-.147-.197t-.165-.183q-.086-.087-.18-.167q-.093-.08-.194-.151t-.207-.132t-.218-.114q-.112-.052-.227-.094q-.116-.041-.235-.073t-.241-.052q-.121-.02-.244-.03M3.5 3.5l17 17");
}

.t171rpktc {
  d: path("M9.75 17.5v-3.8m0-7.9v-.3l9.5-2v11.792m-15 2.208a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
