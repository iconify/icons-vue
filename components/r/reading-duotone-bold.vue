<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fnnwjc5dd"/><path class="n0na4yb0n"/><path class="o2o7qi0tg"/><path class="jq5siqonn"/><path class="t-0jg7bvk"/><path class="x4kxwubfs"/><path class="m0msdy1bm"/><path class="exo870qhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reading-duotone-bold" /></template>
<style>
.exo870qhz {
  d: path("M15 11h4");
}

.fnnwjc5dd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jq5siqonn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m0msdy1bm {
  d: path("M5 11h4");
}

.n0na4yb0n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o2o7qi0tg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-0jg7bvk {
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
}

.x4kxwubfs {
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
}

</style>
