<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-atgz8yl"/><path class="sej2a9tve"/><path class="qhpk1fjmd"/><path class="x2dazdbms"/><path class="fdvd1zxtb"/><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:window-function-duotone-regular" /></template>
<style>
.fdvd1zxtb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 7H21v12h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j-atgz8yl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k9n1nabge {
  d: path("M3 10h12.5");
}

.m45ql5bta {
  d: path("M3 16h12.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ou9p_ybmc {
  d: path("M3 4h12.5");
}

.qhpk1fjmd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s1n7yd_mp {
  d: path("M3 22h12.5");
}

.s92gxib6y {
  d: path("M18.5 7H21v12h-2.5");
}

.sej2a9tve {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2dazdbms {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 22h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
