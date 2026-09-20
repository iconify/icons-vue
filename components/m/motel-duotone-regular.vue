<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i6d4jc9lq"/><path class="v_dlw1bwz"/><path class="vcfvwjbjz"/><path class="f2rvybcyq"/><path class="tahjarbfs"/><path class="rw6ho_bav"/><path class="ftjlxk3sh"/><path class="dgur4c9cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motel-duotone-regular" /></template>
<style>
.dgur4c9cy {
  d: path("M14 21v-3.5h4V21");
}

.f2rvybcyq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftjlxk3sh {
  d: path("M4 21v-3.5h4V21");
}

.i6d4jc9lq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15V5h20v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.tahjarbfs {
  d: path("M2 15V5h20v10");
}

.v_dlw1bwz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vcfvwjbjz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
