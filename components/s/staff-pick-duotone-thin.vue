<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqbuapx8e"/><path class="p3ulwu3dh"/><path class="adxensbci"/><path class="nmwlt6bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staff-pick-duotone-thin" /></template>
<style>
.adxensbci {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmwlt6bbh {
  d: path("m9 8.5 2 2 4 -4");
}

.p3ulwu3dh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 8.5 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xqbuapx8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
