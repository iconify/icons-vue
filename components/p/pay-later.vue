<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cd6rv5bwo"/><circle class="upu83lbfh"/><path class="kwt9vubhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pay-later" /></template>
<style>
.cd6rv5bwo {
  d: path("M11.75 18.75h-6.5a2.5 2.5 0 0 1-2.5-2.5v-8.5a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v3.5m-18.5-2h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwt9vubhj {
  d: path("M17 14.75V17h2");
}

.upu83lbfh {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>
