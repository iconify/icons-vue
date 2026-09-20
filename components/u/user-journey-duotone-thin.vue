<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwgb59c-m"/><path class="tzxtpfb7v"/><path class="k8enhtbpo"/><path class="zrqv5h_fd"/><path class="ncpq3abje"/><path class="yhbbndf5c"/><path class="fd4ngbb9a"/><path class="zohykibek"/><path class="j49v8ng1j"/><path class="fop9i_hvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-journey-duotone-thin" /></template>
<style>
.cwgb59c-m {
  fill: currentColor;
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fd4ngbb9a {
  d: path("m6 17 4 -4");
}

.fop9i_hvr {
  d: path("M19 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j49v8ng1j {
  d: path("m14 9 4 -4");
}

.k8enhtbpo {
  fill: currentColor;
  d: path("M19 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ncpq3abje {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 9 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tzxtpfb7v {
  fill: currentColor;
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yhbbndf5c {
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zrqv5h_fd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
