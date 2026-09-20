<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8c5u6bor"/><path class="uvgrx_yvv"/><path class="phg4z53le"/><path class="jc5wb8hwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-head-outline-thin" /></template>
<style>
.d8c5u6bor {
  d: path("M7 3v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jc5wb8hwy {
  d: path("m12 11 4 4 -4 4 -4 -4Z");
}

.phg4z53le {
  d: path("M17 3v5");
}

.uvgrx_yvv {
  d: path("M12 3v5");
}

</style>
