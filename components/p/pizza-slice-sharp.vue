<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ot6btzbno"/><path class="kjslsjdfn"/><path class="vlneh2rkq"/><path class="mi7a68b3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza-slice-sharp" /></template>
<style>
.kjslsjdfn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 10h.01m-.26 7h.01m7.49.5h.01");
}

.mi7a68b3f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 5.75A5.25 5.25 0 0 1 18.25 11");
}

.ot6btzbno {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.75v7.75h7.75a7.75 7.75 0 1 1-7.75-7.75Zm-.75 7.75h-7m7.75.75v7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vlneh2rkq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 10.25v-7A7.75 7.75 0 0 1 20.75 11H13z");
}

</style>
