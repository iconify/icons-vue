<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nfl06b7ml"/><path class="oo1kzsqpt"/><path class="l_ld7wsnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spa" /></template>
<style>
.l_ld7wsnp {
  d: path("m10.5 9.75l1.5 1.5l-1.5 1.5");
}

.nfl06b7ml {
  d: path("M2.5 2.5h19v19h-19Zm0 4.5h19");
}

.oo1kzsqpt {
  d: path("M15.5 14.75a3.5 3.5 0 1 1-3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
