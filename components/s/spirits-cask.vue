<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lnjctw_uj"/><path class="l_lolebqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spirits-cask" /></template>
<style>
.l_lolebqr {
  d: path("M8.5 5q-1.5 7 0 14m7-14q1.5 7 0 14M12 12h.01");
}

.lnjctw_uj {
  d: path("M5 6q7-2.5 14 0q2.5 6 0 12q-7 2.5-14 0q-2.5-6 0-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
