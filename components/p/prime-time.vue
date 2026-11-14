<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gk0ixkbqr"/><path class="lp_73lv9d"/><path class="ub1bmybzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prime-time" /></template>
<style>
.gk0ixkbqr {
  d: path("M2.5 3.5h19V18h-19Zm6 17.5h7");
}

.lp_73lv9d {
  d: path("M7.5 10.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ub1bmybzl {
  d: path("M12 9v1.75l-1.5 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
