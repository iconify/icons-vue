<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k38v4qb6f"/><path class="b7uyqxwtl"/><path class="xsv2fybbr"/><path class="mz63nabpb"/><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="gnhsdzb8d"/><path class="elmoo_bpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:payslip-duotone-thin" /></template>
<style>
.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.elmoo_bpw {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gnhsdzb8d {
  d: path("M6 13h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k38v4qb6f {
  fill: currentColor;
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.mz63nabpb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xsv2fybbr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwh7a2bjz {
  d: path("M6 9h9");
}

</style>
