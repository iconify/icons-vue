<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_vo3wz-j"/><path class="fti-unbge"/><path class="ry7zsib4b"/><path class="ru5hm3b_s"/><path class="gg64dgbvc"/><path class="ts7vm2b5m"/><path class="fozhwebbv"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="uzmclv6tb"/><path class="fhumgwb1z"/><path class="ko65glbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:node-cluster-duotone-regular" /></template>
<style>
.aq5i5tblx {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fhumgwb1z {
  d: path("m10.5 9.5 -3 3");
}

.fozhwebbv {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fti-unbge {
  fill: currentColor;
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gg64dgbvc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10.5 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ko65glbqt {
  d: path("m13.5 9.5 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p83l94bht {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ru5hm3b_s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ry7zsib4b {
  fill: currentColor;
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_vo3wz-j {
  fill: currentColor;
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ts7vm2b5m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13.5 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uzmclv6tb {
  d: path("M12 8v3");
}

</style>
