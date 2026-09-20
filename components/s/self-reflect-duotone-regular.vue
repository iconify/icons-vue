<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q_e2fy9uw"/><path class="xbjl58b2q"/><path class="l_ubjkyka"/><path class="uy91f4czm"/><path class="y07a50u1t"/><path class="an_usn22t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-reflect-duotone-regular" /></template>
<style>
.an_usn22t {
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
}

.l_ubjkyka {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q_e2fy9uw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uy91f4czm {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

.xbjl58b2q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
