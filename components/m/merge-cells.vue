<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qzkvbx_uy"/><path class="qyjnv-bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:merge-cells" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyjnv-bnb {
  d: path("M12 4.75v3.5m0 7.5v3.5M5.75 12h4M8 10l2 2l-2 2m10.25-2h-4M16 10l-2 2l2 2");
}

.qzkvbx_uy {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
