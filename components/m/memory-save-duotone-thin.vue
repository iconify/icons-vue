<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hc7tfacqy"/><path class="z71hb1bfe"/><path class="x3s2sybcg"/><path class="vnsh5xb1c"/><path class="x0vbjnqyj"/><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-save-duotone-thin" /></template>
<style>
.czv374byt {
  d: path("M10 16h11");
}

.gzf8q_b5i {
  d: path("m5 9 2 2 -2 2");
}

.hc7tfacqy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i33dqh0th {
  d: path("M10 11h11");
}

.pv9xj1b7g {
  d: path("M2 11h5");
}

.vnsh5xb1c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x0vbjnqyj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3s2sybcg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7gyblbnl {
  d: path("M10 6h11");
}

.z71hb1bfe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 9 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
