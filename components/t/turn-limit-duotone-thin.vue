<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6glnqdag"/><path class="eid_r_b9d"/><path class="fw_wgnb2f"/><path class="ml617mhdr"/><path class="vgrmyb3pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:turn-limit-duotone-thin" /></template>
<style>
.eid_r_b9d {
  fill: currentColor;
  d: path("M7 15a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fw_wgnb2f {
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml617mhdr {
  d: path("M7 15a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.u6glnqdag {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vgrmyb3pe {
  d: path("M20.5 4v16");
}

</style>
