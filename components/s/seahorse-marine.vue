<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l7-odytvd"/><path class="f1hs9xb7j"/><path class="ldnins8me"/><path class="p7kch90yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seahorse-marine" /></template>
<style>
.f1hs9xb7j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7c.25-2.25 1.5-3.75 3-3.75l.75-.5l.75.75c1.25.5 2 1.75 1.5 3.25s1.5 2.75 1.5 5.75c0 2.5-1.75 4.25-4 4.75C10 17 8.5 13.5 10 10.75c.75-1.25.75-2.25-.25-3.75m0 .25l-5.5.5");
}

.l7-odytvd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.63 11.03l1.84.94q.53.28.02.59l-1.88 1.13q-.51.31-.51-.29v-2.05q0-.6.53-.32");
}

.ldnins8me {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 6h.01");
}

.p7kch90yj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 17.25c.75 2 0 4-2 4c-1.25 0-2-.75-2-1.75s.75-1.5 1.5-1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
