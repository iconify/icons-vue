<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-cg_ib1f"/><path class="dwqtbeylw"/><path class="zuuhu6bzg"/><path class="nreph_b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:measuring-cup-outline-thin" /></template>
<style>
.dwqtbeylw {
  d: path("M6 11h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nreph_b_j {
  d: path("M17 9a3 3 0 0 1 0 6");
}

.u-cg_ib1f {
  d: path("M5 6v13h12V6");
}

.zuuhu6bzg {
  d: path("M6 15h6");
}

</style>
