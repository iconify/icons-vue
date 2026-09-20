<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="jm3xd8egv"/><path class="ssdglbbuh"/><path class="hiwkq4bpu"/><path class="oid8kdbim"/><path class="zugrvnb7t"/><path class="f5ieidcch"/><path class="q40roytdv"/><path class="gr2yy8pwl"/><path class="pkf-n2b8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:workshop-duotone-thin" /></template>
<style>
.f_hy4hbgg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f5ieidcch {
  d: path("M5 13v8");
}

.gr2yy8pwl {
  d: path("M8 13V6h9v7");
}

.hiwkq4bpu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 13V6h9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm3xd8egv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oid8kdbim {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 6a2.5 2.5 0 0 1 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pkf-n2b8h {
  d: path("M10 6a2.5 2.5 0 0 1 5 0");
}

.q40roytdv {
  d: path("M19 13v8");
}

.ssdglbbuh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
