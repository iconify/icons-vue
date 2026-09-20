<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kk1vrmiqz"/><path class="kp6e_l5bx"/><path class="k492cm1wp"/><path class="uy91f4czm"/><path class="y07a50u1t"/><path class="an_usn22t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-reflect-duotone-bold" /></template>
<style>
.an_usn22t {
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
}

.k492cm1wp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kk1vrmiqz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kp6e_l5bx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uy91f4czm {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
