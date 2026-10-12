<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mwsfgo77v"/><path class="zxts1xnci"/><path class="xvdt55bhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toadstool-sharp" /></template>
<style>
.mwsfgo77v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11C2.75 7.25 7 4.25 12 4.25s9.25 3 9.25 6.75v1.25H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xvdt55bhc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12.25h3l.25 5.25l2 .8v2.95h-7.5V18.3l2-.8Z");
}

.zxts1xnci {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9.25h.01m4.99-2h.01m4.99 2h.01");
}

</style>
