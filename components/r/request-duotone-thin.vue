<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ak588yg4c"/><path class="pmhsn037r"/><path class="lezu57blc"/><path class="ct75s-bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:request-duotone-thin" /></template>
<style>
.ak588yg4c {
  fill: currentColor;
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ct75s-bnk {
  d: path("m12 9 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lezu57blc {
  d: path("M2 12h13");
}

.pmhsn037r {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
