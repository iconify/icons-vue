<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ulkm_35ny"/><path class="fo_a7xbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ph-scale" /></template>
<style>
.fo_a7xbqe {
  d: path("M6.45 11v6.5m3.7-6.5v6.5m3.7-6.5v6.5m3.7-6.5v6.5M10.5 3.75h3q.75 0 .38.65l-1.51 2.7q-.37.65-.74 0l-1.51-2.7q-.37-.65.38-.65");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulkm_35ny {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 11px;
  rx: 2px;
}

</style>
