<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbr--mb3k"/><path class="mkh6f026t"/><path class="x2p3-nb6i"/><path class="sgp7fvbwx"/><path class="c1g0k8fft"/><path class="k6nj2fbya"/><path class="a6mnjib5x"/><path class="xedmbxbzm"/><path class="l8vricc3a"/><path class="yngda3bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:null-fill-duotone-regular" /></template>
<style>
.a6mnjib5x {
  d: path("M3 10h4");
}

.c1g0k8fft {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.l8vricc3a {
  d: path("M17 10h4");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgp7fvbwx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbr--mb3k {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x2p3-nb6i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
