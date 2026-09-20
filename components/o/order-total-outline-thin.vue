<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd_dotbnq"/><path class="h2fnwccfy"/><path class="g-zzhsbrv"/><path class="cta_b6xgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:order-total-outline-thin" /></template>
<style>
.cta_b6xgu {
  d: path("M14.5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g-zzhsbrv {
  d: path("M7 10h6");
}

.h2fnwccfy {
  d: path("M7 6h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

</style>
