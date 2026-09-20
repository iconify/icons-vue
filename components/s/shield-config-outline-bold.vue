<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymp2b4b6u"/><path class="v5he4mb3o"/><path class="c0j5uhb3y"/><path class="w0sebyb3m"/><path class="epr-ge8_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shield-config-outline-bold" /></template>
<style>
.c0j5uhb3y {
  d: path("M13.5 7.5v4");
}

.epr-ge8_k {
  d: path("M10.5 11.5v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v5he4mb3o {
  d: path("M9 9.5h6");
}

.w0sebyb3m {
  d: path("M9 13.5h6");
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
