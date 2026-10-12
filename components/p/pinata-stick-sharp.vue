<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nf047vbjz"/><path class="r8j-njbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinata-stick-sharp" /></template>
<style>
.nf047vbjz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.64 3.32l1.04 2.29l.14.32l.35.04l2.5.27l.35.04l-.26.24l-1.86 1.69l-.26.24l.07.34l.51 2.46l.07.34l-.3-.17l-2.19-1.25l-.3-.17l-.3.17l-2.19 1.25l-.3.17l.07-.34l.51-2.46l.07-.34l-.26-.24l-1.86-1.69l-.26-.24l.35-.04l2.5-.27l.35-.04l.14-.32l1.04-2.29l.14-.32zM3.33 20.33l.34.34l.71.71l.71-.71l6.33-6.33l.71-.71l-.71-.71l-.34-.34l-.71-.71l-.71.71l-6.33 6.33l-.71.71zM5.6 16.6l1.8 1.8m1.2-4.8l1.8 1.8");
}

.r8j-njbfo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 15.5h.01m3.24-.75h.01m-1.26 3.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
