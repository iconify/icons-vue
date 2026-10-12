<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="jvrnx2_0k"/><path class="w3cjqe6oj"/><path class="c74n7obrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:virus-sharp" /></template>
<style>
.c74n7obrr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 12h.01m-2.43 5.83h.01M12 20.25h.01m-5.84-2.42h.01M3.75 12h.01m2.41-5.83h.01M12 3.75h.01m5.82 2.42h.01m-7.59 4.58h.01m3.49 2.5h.01");
}

.jvrnx2_0k {
  cx: 12px;
  cy: 12px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w3cjqe6oj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 12h1.25m-3.01 4.24l.89.89M12 18v1.25m-4.24-3.01l-.89.89M6 12H4.75m3.01-4.24l-.89-.89M12 6V4.75m4.24 3.01l.89-.89");
}

</style>
