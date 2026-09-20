<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_vo3wz-j"/><path class="fti-unbge"/><path class="ry7zsib4b"/><path class="dh-2h3b4q"/><path class="w28zymbxd"/><path class="rv4rj1bxi"/><path class="fozhwebbv"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="uzmclv6tb"/><path class="fhumgwb1z"/><path class="ko65glbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:node-cluster-duotone-thin" /></template>
<style>
.aq5i5tblx {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dh-2h3b4q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko65glbqt {
  d: path("m13.5 9.5 3 3");
}

.p83l94bht {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rv4rj1bxi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13.5 9.5 3 3");
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

.uzmclv6tb {
  d: path("M12 8v3");
}

.w28zymbxd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10.5 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
