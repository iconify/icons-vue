<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ejurvtcbm"/><path class="zfee3fbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meter-battery" /></template>
<style>
.ejurvtcbm {
  d: path("M2.5 5h17v14h-17Zm19 4.5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfee3fbnz {
  d: path("M5.5 15.5a5.5 5.5 0 0 1 11 0m-5.5 0l1.25-2");
}

</style>
