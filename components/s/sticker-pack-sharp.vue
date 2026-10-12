<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ige9aos1v"/><path class="pymd8db-g"/><path class="mtb_j2b3h"/><path class="cewy72bjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticker-pack-sharp" /></template>
<style>
.cewy72bjj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 12.5l2.086 2.568L12.5 13.5");
}

.ige9aos1v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h15.5V12l-2.12 2.12l-5.01 5.01L12 21.25H2.75V2.75z");
}

.mtb_j2b3h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 8.25h.01m4.99 0h.01");
}

.pymd8db-g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.22 14.03l-5.19 5.19l-.53.53V15l.53-.53l.44-.44l.53-.53h4.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
