<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="xx4t1ib_x"/><path class="hfr86bw5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tablet-landscape" /></template>
<style>
.hfr86bw5l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 12h.01");
}

.xx4t1ib_x {
  width: 18.5px;
  height: 16px;
  x: 2.75px;
  y: 4px;
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
