<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo12c8bss"/><path class="hf_gtezns"/><path class="k7ywiznno"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:probability-curve-duotone-thin" /></template>
<style>
.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo12c8bss {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k7ywiznno {
  d: path("M4 14a8 8 0 0 1 16 0");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
