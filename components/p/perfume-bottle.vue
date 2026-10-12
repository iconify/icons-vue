<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="befzp7bcu"/><rect class="vt6tpd78t"/><rect class="zgvebibfk"/><path class="rti6afb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:perfume-bottle" /></template>
<style>
.befzp7bcu {
  width: 6px;
  height: 3.5px;
  x: 9px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.rti6afb8w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 4.5h.01");
}

.vt6tpd78t {
  width: 3px;
  height: 4.25px;
  x: 10.5px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgvebibfk {
  width: 12.5px;
  height: 10.75px;
  x: 5.75px;
  y: 10.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

</style>
