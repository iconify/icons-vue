<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="siwmoobxp"/><path class="kl3l7ufvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shirt-name" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl3l7ufvb {
  d: path("M11 12h2a1.75 1.75 0 0 1 1.75 1.75V14A1.75 1.75 0 0 1 13 15.75h-2A1.75 1.75 0 0 1 9.25 14v-.25A1.75 1.75 0 0 1 11 12");
}

.siwmoobxp {
  d: path("M8 3L2.5 6.5l2 4.5l2-1v11h11V10l2 1l2-4.5L16 3q-4 3-8 0");
}

</style>
