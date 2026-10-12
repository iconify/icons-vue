<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p5w6duoas"/><circle class="e-2-i017w"/><path class="k2u08qglx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steering-wheel" /></template>
<style>
.e-2-i017w {
  cx: 12px;
  cy: 12px;
  r: 2.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2u08qglx {
  d: path("M2.75 12h6.5m5.5 0h6.5M12 14.75v6.5");
}

.p5w6duoas {
  d: path("M12 2.75a9.25 9.25 0 1 0 0 18.5a9.25 9.25 0 0 0 0-18.5");
}

</style>
