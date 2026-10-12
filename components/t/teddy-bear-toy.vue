<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qe03z35cg"/><circle class="ot-ydxb8o"/><path class="qlw0k9bam"/><circle class="d-8clwncb"/><circle class="cbq7e-b9e"/><path class="e40u1lb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teddy-bear-toy" /></template>
<style>
.cbq7e-b9e {
  cx: 18.75px;
  cy: 15px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d-8clwncb {
  cx: 5.25px;
  cy: 15px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.e40u1lb6y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.9 6.75h.01m2.19 0h.01");
}

.ot-ydxb8o {
  cx: 12px;
  cy: 7px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe03z35cg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.33 6.33a1.75 1.75 0 1 1 2-2a2.75 2.75 0 0 0-2 2m3.34-2a1.75 1.75 0 1 1 2 2a2.75 2.75 0 0 0-2-2");
}

.qlw0k9bam {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 12.25h1a3.5 3.5 0 0 1 3.5 3.5v4a1.5 1.5 0 0 1-1.5 1.5H14a.5.5 0 0 1-.5-.5v-1a1.5 1.5 0 0 0-3 0v1a.5.5 0 0 1-.5.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-4a3.5 3.5 0 0 1 3.5-3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
