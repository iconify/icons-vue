<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yjl6rx25o"/><path class="xzbn7sr9p"/><path class="nzkqxpbbf"/><path class="p3-4dp1vz"/><path class="tahjarbfs"/><path class="rw6ho_bav"/><path class="ftjlxk3sh"/><path class="dgur4c9cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motel-duotone-bold" /></template>
<style>
.dgur4c9cy {
  d: path("M14 21v-3.5h4V21");
}

.ftjlxk3sh {
  d: path("M4 21v-3.5h4V21");
}

.nzkqxpbbf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p3-4dp1vz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tahjarbfs {
  d: path("M2 15V5h20v10");
}

.xzbn7sr9p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjl6rx25o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15V5h20v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
