<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eff5yibna"/><path class="rpyanp93e"/><path class="bb5x-w5-m"/><path class="jycpvgb1i"/><path class="xa9vorq4l"/><path class="pq9ly31-r"/><path class="iup9trbmr"/><path class="w92rm08yv"/><path class="t0-mwc0xy"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:n-plus-one-duotone-bold" /></template>
<style>
.bb5x-w5-m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16v-6h16v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iup9trbmr {
  d: path("M12 6v4");
}

.jycpvgb1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rpyanp93e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.w92rm08yv {
  d: path("M4 16v-6h16v6");
}

.xa9vorq4l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
