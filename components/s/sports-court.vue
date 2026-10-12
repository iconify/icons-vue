<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k7proqgrm"/><path class="zgd95bcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sports-court" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7proqgrm {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 1.5px;
}

.zgd95bcmm {
  d: path("M12 5.25v13.5m-9.25-9.5h3.5v5.5h-3.5m18.5-5.5h-3.5v5.5h3.5M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
