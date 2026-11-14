<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcohlc8yr"/><path class="sr3eq2b4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:virtual-dom" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcohlc8yr {
  d: path("M11.625 2.5h.75A2.625 2.625 0 0 1 15 5.125v.25A2.625 2.625 0 0 1 12.375 8h-.75A2.625 2.625 0 0 1 9 5.375v-.25A2.625 2.625 0 0 1 11.625 2.5M3.25 18.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m12 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M12 8v3.75");
}

.sr3eq2b4a {
  d: path("M6 15.5v-3.75h12v3.75");
}

</style>
