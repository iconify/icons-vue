<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g4_qklztr"/><circle class="orr73zjqz"/><path class="ba32btbbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transfer" /></template>
<style>
.ba32btbbz {
  d: path("M16.25 12h5M18.5 9.25L21.25 12l-2.75 2.75");
}

.g4_qklztr {
  cx: 8.5px;
  cy: 12px;
  r: 5.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.orr73zjqz {
  cx: 8.5px;
  cy: 12px;
  r: 2.5px;
}

</style>
