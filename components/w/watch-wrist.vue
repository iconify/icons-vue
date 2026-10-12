<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evew35b2m"/><circle class="pfpt48slt"/><path class="zag8i3elj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watch-wrist" /></template>
<style>
.evew35b2m {
  d: path("M9.25 7.25v-3.5a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1v3.5m-5.5 9.5v3.5a1 1 0 0 0 1 1h3.5a1 1 0 0 0 1-1v-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

.zag8i3elj {
  d: path("M17.5 12h1.75M12 9.25V12l2 1.25");
}

</style>
