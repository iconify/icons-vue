<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jn8357bzn"/><path class="ong8qwbtp"/><path class="p_h3un67t"/><path class="hmrmv33is"/><path class="wthryk-vz"/><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-save-duotone-bold" /></template>
<style>
.czv374byt {
  d: path("M10 16h11");
}

.gzf8q_b5i {
  d: path("m5 9 2 2 -2 2");
}

.hmrmv33is {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i33dqh0th {
  d: path("M10 11h11");
}

.jn8357bzn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ong8qwbtp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 9 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p_h3un67t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pv9xj1b7g {
  d: path("M2 11h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wthryk-vz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7gyblbnl {
  d: path("M10 6h11");
}

</style>
