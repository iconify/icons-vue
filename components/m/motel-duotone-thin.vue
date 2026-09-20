<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk1w1tchk"/><path class="x4r46rbgt"/><path class="cnwtrqmag"/><path class="uly3_zloy"/><path class="tahjarbfs"/><path class="rw6ho_bav"/><path class="ftjlxk3sh"/><path class="dgur4c9cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motel-duotone-thin" /></template>
<style>
.cnwtrqmag {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dgur4c9cy {
  d: path("M14 21v-3.5h4V21");
}

.ftjlxk3sh {
  d: path("M4 21v-3.5h4V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.tahjarbfs {
  d: path("M2 15V5h20v10");
}

.uk1w1tchk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15V5h20v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uly3_zloy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x4r46rbgt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
