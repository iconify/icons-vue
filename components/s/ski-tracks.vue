<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcauwkbvm"/><path class="ighr8abuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-tracks" /></template>
<style>
.hcauwkbvm {
  d: path("M6 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ighr8abuq {
  d: path("M10 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

</style>
