<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v7k_gnx8j"/><path class="povs9wlph"/><path class="arlddp6_a"/><path class="q4yaf_b-b"/><path class="xw66a0v9s"/><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-save-duotone-regular" /></template>
<style>
.arlddp6_a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.czv374byt {
  d: path("M10 16h11");
}

.gzf8q_b5i {
  d: path("m5 9 2 2 -2 2");
}

.i33dqh0th {
  d: path("M10 11h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.povs9wlph {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 9 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pv9xj1b7g {
  d: path("M2 11h5");
}

.q4yaf_b-b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7k_gnx8j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7gyblbnl {
  d: path("M10 6h11");
}

.xw66a0v9s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
