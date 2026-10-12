<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n1_okeddq"/><path class="dbxmtdbha"/><path class="lveyj8b2h"/><path class="ia68ed4ig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-print-sharp" /></template>
<style>
.dbxmtdbha {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 9.5h.01");
}

.ia68ed4ig {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.25 19.75l3-3L12 19.5m-.75-1l1.25-1.25l2.5 2.5");
}

.lveyj8b2h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.75h11.5v7.5H6.25v-1.5Z");
}

.n1_okeddq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6.25v-3.5h10.5v3.5m-14.5 0h18.5v7.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
