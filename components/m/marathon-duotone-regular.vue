<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_11v4jkg"/><path class="joq1gpb1d"/><path class="dmo4ekbop"/><path class="f5c56wlhk"/><path class="fnbgpcbhf"/><path class="uqqniu6bc"/><path class="j2-drqnzq"/><path class="lp-jzobeh"/><path class="lvrweqtce"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:marathon-duotone-regular" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.dmo4ekbop {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f5c56wlhk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 15 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2-drqnzq {
  d: path("m13 7 -4 4 4 4");
}

.joq1gpb1d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 7 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lp-jzobeh {
  d: path("M9 11H5");
}

.lvrweqtce {
  d: path("m13 15 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_11v4jkg {
  fill: currentColor;
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uqqniu6bc {
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
