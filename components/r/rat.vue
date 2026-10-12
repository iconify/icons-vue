<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="llz0v_uwq"/><path class="i_z9_qb5y"/><path class="w722ch5gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rat" /></template>
<style>
.i_z9_qb5y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 9.25C7.75 7.75 9 6.5 10.5 7m8.5 6.75c1.5.5 2.25 1.75 2.25 3.25c0 2-1.5 3.25-3.5 3.5M8 17.25v2.25m6-2.25v2.25");
}

.llz0v_uwq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13c0-.5.3-.9.75-1.1l3-1.4c1.5-1.75 3.75-2.75 6.25-2.75c3.75 0 6.25 2.5 6.25 5.75c0 2.25-1.5 3.75-3.75 3.75h-7.5C6 17.25 4.5 15.5 3.4 14c-.4-.25-.65-.6-.65-1");
}

.w722ch5gx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 11.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
