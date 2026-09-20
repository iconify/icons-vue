<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n48w5yb-p"/><path class="ycb-w6pqj"/><path class="abtetbcpu"/><path class="vfsdtf5fr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:panel-left-dashed-outline-thin" /></template>
<style>
.abtetbcpu {
  d: path("M9 10.5v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n48w5yb-p {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.vfsdtf5fr {
  d: path("M9 16v3");
}

.ycb-w6pqj {
  d: path("M9 5v3");
}

</style>
