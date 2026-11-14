<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j348v_b-z"/><path class="uwnhjfn9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-marked" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j348v_b-z {
  d: path("m4.077 5.551l4.25-1.771a1.75 1.75 0 0 1 1.346 0l4.654 1.94a1.75 1.75 0 0 0 1.346 0l2.904-1.21A1.75 1.75 0 0 1 21 6.125V10.5a1.75 1.75 0 0 1-1.75 1.75h-4.275a1.75 1.75 0 0 0-1.238.513l-.974.974a1.75 1.75 0 0 0-.513 1.238v2.534a1.196 1.196 0 0 1-1.625 1.116l-.971-.373a1.75 1.75 0 0 0-1.301.018l-2.93 1.22A1.75 1.75 0 0 1 3 17.875V7.167a1.75 1.75 0 0 1 1.077-1.616M9 3.5V18m6-12v3.5");
}

.uwnhjfn9z {
  d: path("M18 21.5S15 19 15 17a3 3 0 0 1 6 0c0 2-3 4.5-3 4.5m0-4.5h.01");
}

</style>
