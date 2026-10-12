<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a_ujwacgt"/><circle class="gzk5d2xwl"/><path class="gu8uj_bfl"/><path class="p4g45hywd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rabbit-sharp" /></template>
<style>
.a_ujwacgt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11.28L5.6 6l-.483-1.688l3.3-1.2L8.9 4.8l1.6 4.64m6 1.84L18.4 6l.483-1.688l-3.3-1.2L15.1 4.8l-1.6 4.64");
}

.gu8uj_bfl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 14.5h.01m4.49 0h.01");
}

.gzk5d2xwl {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4g45hywd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 17.25h1.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
