<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eff5yibna"/><path class="n74qqnw0j"/><path class="f1vz2n_od"/><path class="pen5ukb_h"/><path class="xdhl9rnnf"/><path class="pq9ly31-r"/><path class="iup9trbmr"/><path class="w92rm08yv"/><path class="t0-mwc0xy"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:n-plus-one-duotone-regular" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f1vz2n_od {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16v-6h16v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iup9trbmr {
  d: path("M12 6v4");
}

.n74qqnw0j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pen5ukb_h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.w92rm08yv {
  d: path("M4 16v-6h16v6");
}

.xdhl9rnnf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
