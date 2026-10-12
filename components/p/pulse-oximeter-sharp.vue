<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nkpv0jb_u"/><path class="f-kusjufu"/><path class="tr1qcbctt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pulse-oximeter-sharp" /></template>
<style>
.f-kusjufu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25H16.5v3.5H2.75Z");
}

.nkpv0jb_u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5.25h14.5v13.5H6.75z");
}

.tr1qcbctt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7.75h.01m2.99 0h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
