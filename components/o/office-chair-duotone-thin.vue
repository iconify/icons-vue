<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xwxt0ub6g"/><path class="mz5kvibtp"/><path class="vxy4ztabh"/><path class="w5i79a2na"/><path class="t8olluqaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:office-chair-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz5kvibtp {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.t8olluqaw {
  d: path("m7 21 3 -3h4l3 3");
}

.vxy4ztabh {
  d: path("M4 14h16");
}

.w5i79a2na {
  d: path("M12 14v4");
}

.xwxt0ub6g {
  fill: currentColor;
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
