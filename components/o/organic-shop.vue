<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g3fv5ukgr"/><path class="mh_31yvmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:organic-shop" /></template>
<style>
.g3fv5ukgr {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.8m-15-.8v9.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mh_31yvmo {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m4.5 1c0-5 2-7 6.5-7c0 4.5-2 7-6.5 7m0 0l4-4");
}

</style>
