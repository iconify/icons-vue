<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_b8y0_wc"/><path class="i3qzpz26g"/><path class="pxhtn-byk"/><path class="f5y0d7xbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trend-down-duotone-thin" /></template>
<style>
.f5y0d7xbc {
  d: path("M17 17h4v-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_b8y0_wc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 6 6 4 -4 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i3qzpz26g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 17h4v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pxhtn-byk {
  d: path("m3 7 6 6 4 -4 8 8");
}

</style>
