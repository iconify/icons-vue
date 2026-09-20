<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcjv44b9n"/><path class="m3s7nnbex"/><path class="vl47r8b0v"/><path class="t9gnp4b0n"/><path class="atsab9b_m"/><path class="qxhe48bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parasol-duotone-thin" /></template>
<style>
.atsab9b_m {
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m3s7nnbex {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.rcjv44b9n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.vl47r8b0v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
