<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hu8yjkb5z"/><path class="nfs3xabro"/><path class="zeh16hb8v"/><path class="nlyctxb4h"/><path class="fxhu6xblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:order-tracking-sharp" /></template>
<style>
.fxhu6xblw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 7h.01");
}

.hu8yjkb5z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.75h9.5v9.5h-9.5z");
}

.nfs3xabro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11.75v3h3v-3");
}

.nlyctxb4h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 14.25s-4.25-3.9-4.25-7.25a4.25 4.25 0 0 1 8.5 0c0 3.35-4.25 7.25-4.25 7.25Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zeh16hb8v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 18.75h.01m3.24 0h.01");
}

</style>
