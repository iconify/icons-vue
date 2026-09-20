<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="oe9x1ac1i"/><path class="d9764sboq"/><path class="y4g-ojbgk"/><path class="k6nj2fbya"/><path class="r1-ktgx-e"/><path class="nmmozg1gr"/><path class="t33f_gbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outline-gen-duotone-regular" /></template>
<style>
.d9764sboq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nmmozg1gr {
  d: path("M7 15h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe9x1ac1i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1-ktgx-e {
  d: path("M7 10h14");
}

.t33f_gbzo {
  d: path("M11 20h10");
}

.y4g-ojbgk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
