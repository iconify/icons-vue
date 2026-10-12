<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wd17rndys"/><path class="ltojl_pmm"/><rect class="b5htw7bfh"/><path class="c_4hrcb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-set" /></template>
<style>
.b5htw7bfh {
  width: 4.5px;
  height: 16.5px;
  x: 16.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.c_4hrcb3k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 8h.01M19 12h.01M19 16h.01");
}

.ltojl_pmm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 8h5m-5 4h5m-5 4h5");
}

.wd17rndys {
  width: 11.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
