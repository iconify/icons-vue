<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mpxubccrr"/><path class="o35gkxngb"/><path class="pf60eubcf"/><path class="mzs9lvbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stuck-agent-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpxubccrr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mzs9lvbbs {
  d: path("M19.5 4v16");
}

.o35gkxngb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pf60eubcf {
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
