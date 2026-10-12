<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cd8ylgg9y"/><path class="fz7_s5e9g"/><path class="sb2uf-bwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ticket-stub-sharp" /></template>
<style>
.cd8ylgg9y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.25v-1.5h14v15.5L17.25 18l-1.75 1.25L13.75 18L12 19.25L10.25 18L8.5 19.25L6.75 18L5 19.25Z");
}

.fz7_s5e9g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.15 6.62l.49 1.17l.15.37l.4.03l1.26.1l.4.03l-.3.26l-.96.83l-.31.26l.1.39l.29 1.23l.09.39l-.34-.21l-1.08-.66l-.34-.21l-.34.21l-1.08.66l-.34.21l.09-.39l.29-1.23l.1-.39l-.31-.26l-.96-.83l-.3-.26l.4-.03l1.26-.1l.4-.03l.15-.37l.49-1.17l.15-.37z");
}

.sb2uf-bwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 14.25h.01m2.24 0h.01m2.49 0h.01m2.49 0h.01m2.24 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
