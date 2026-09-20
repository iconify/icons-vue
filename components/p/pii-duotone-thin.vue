<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr5if0b2e"/><path class="ppbx_abyw"/><path class="tvr_k_bbt"/><path class="gsl5knvuq"/><path class="axsqg_b2b"/><path class="rjbfcabog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pii-duotone-thin" /></template>
<style>
.axsqg_b2b {
  d: path("M15 12h4");
}

.gsl5knvuq {
  d: path("M15 8h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr5if0b2e {
  fill: currentColor;
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ppbx_abyw {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.rjbfcabog {
  d: path("M17 16h4");
}

.tvr_k_bbt {
  d: path("M4 19a5 5 0 0 1 10 0");
}

</style>
