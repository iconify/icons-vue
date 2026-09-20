<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lusaj0-0f"/><path class="zl6g0h25d"/><path class="av-slcbjo"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tsunami-duotone-thin" /></template>
<style>
.av-slcbjo {
  d: path("M2 17a10 10 0 0 1 18 -6 5 5 0 0 0 -8 0");
}

.cjsg0ab2y {
  d: path("M2 20h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lusaj0-0f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17a10 10 0 0 1 18 -6 5 5 0 0 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl6g0h25d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
