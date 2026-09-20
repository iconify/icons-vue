<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7c_b1bsn"/><path class="erqf8ibjb"/><path class="q07wp9b_c"/><path class="a218-cpca"/><path class="h7bcztycq"/><path class="d8gf8fboh"/><path class="nt94z-wbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:segregation-of-duties-duotone-regular" /></template>
<style>
.a218-cpca {
  d: path("M4 5h16a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2v-3a2 2 0 0 0 0 -4V7a2 2 0 0 1 2 -2");
}

.d8gf8fboh {
  d: path("M7.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.erqf8ibjb {
  fill: currentColor;
  d: path("M7.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h7bcztycq {
  d: path("M12 8v8");
}

.n7c_b1bsn {
  fill: currentColor;
  d: path("M4 5h16a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2v-3a2 2 0 0 0 0 -4V7a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nt94z-wbn {
  d: path("M14.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q07wp9b_c {
  fill: currentColor;
  d: path("M14.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
