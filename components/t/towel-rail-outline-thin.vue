<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="kif6g-eik"/><path class="enh0e8a0v"/><path class="hczrfxb9f"/><path class="qtxvlht3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:towel-rail-outline-thin" /></template>
<style>
.enh0e8a0v {
  d: path("M21 5v3");
}

.hczrfxb9f {
  d: path("M8 5v15h8V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.kif6g-eik {
  d: path("M3 5v3");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

</style>
