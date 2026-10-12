<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vo3rmzklu"/><path class="jzli4zqdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-debris-sharp" /></template>
<style>
.jzli4zqdw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4.5h.01m3.99 2h.01M11.5 21h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vo3rmzklu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.38 7.59l4.49-2.93l.63-.41l.31.68l1.63 3.64l.31.68l-.64.39l-3.72 2.22l-.64.39l-.43-.61l-2.14-3.03L2.75 8zm9.51 5.27l4.47-2.72l.64-.39l.39.64l2.22 3.72l.39.64l-.64.39l-4.47 2.72l-.64.39l-.39-.64l-2.22-3.72l-.39-.64zm2.36-1.11L18 16.5m-13.28.34l2.81-.93l.47-.16l.12.49l.76 3.02l.12.49l-.47.16l-2.81.93l-.47.16l-.12-.49l-.76-3.02l-.12-.49z");
}

</style>
