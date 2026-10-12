<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ptkd2vb_g"/><path class="naovaobih"/><path class="g-5u-ac8w"/><path class="hruw0ckxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toaster-oven-sharp" /></template>
<style>
.g-5u-ac8w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 10h.01m-.01 4.25h.01");
}

.hruw0ckxt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 18.25v2.5m11.5-2.5v2.5");
}

.naovaobih {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9.25h6.5v6H6v-6zm-1 3h7.5");
}

.ptkd2vb_g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v12H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
