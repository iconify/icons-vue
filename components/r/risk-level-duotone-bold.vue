<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="gam3cw54g"/><path class="b7mhs2bzu"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="hqoi59sxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:risk-level-duotone-bold" /></template>
<style>
.b7mhs2bzu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c4fme0p6q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hqoi59sxr {
  d: path("M12 9v7");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
