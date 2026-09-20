<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="get7uzb4k"/><path class="rmyai5brx"/><path class="xgrfb-bqu"/><path class="wwnbqi33p"/><path class="nu1_4q-9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subtask-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.get7uzb4k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10v6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nu1_4q-9l {
  d: path("M14 16h7");
}

.rmyai5brx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwnbqi33p {
  d: path("M6 10v6h5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
