<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="gam3cw54g"/><path class="x8irqac3h"/><path class="qe12h9bwz"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="dv6re0b-t"/><path class="ogqckebrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recovery-score-duotone-bold" /></template>
<style>
.c4fme0p6q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dv6re0b-t {
  d: path("M12 16V8");
}

.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.ogqckebrf {
  d: path("m9 11 3 -3 3 3");
}

.qe12h9bwz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 11 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x8irqac3h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
