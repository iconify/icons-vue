<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cmbugs59v"/><path class="on78oebbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:razor-blade-sharp" /></template>
<style>
.cmbugs59v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v11.5H2.75zM8 12h8");
}

.on78oebbl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12h.01M19 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
