<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lfhwsu5-f"/><path class="g_2kelbcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moose" /></template>
<style>
.g_2kelbcc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 12h.01m2.99 0h.01m-2.76 6h.01m2.49 0h.01");
}

.lfhwsu5-f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9.5h6q.75 3 .75 6l.35 1.75c.3 1.6-.75 3-2.25 3h-3.7c-1.5 0-2.55-1.4-2.25-3l.35-1.75q0-3 .75-6M7.5 7.75C6 7.75 4.5 7 3.5 6c-.6-.6-.65-1.65-.5-2.75l1.5 1L5.5 3l1 1.25l1.25-1L8.5 4.5l1-.5c0 1.5-.75 3.25-2 3.75m9 0c1.5 0 3-.75 4-1.75c.6-.6.65-1.65.5-2.75l-1.5 1l-1-1.25l-1 1.25l-1.25-1l-.75 1.25l-1-.5c0 1.5.75 3.25 2 3.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
