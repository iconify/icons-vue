<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c-z8auf5h"/><path class="m4r17wx7o"/><path class="iwpmudbrd"/><path class="jgj73lbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tiny-house" /></template>
<style>
.c-z8auf5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16.4v-5.05q0-.6-.6-.6h-.55q-.6 0-.14-.39l6.83-5.72q.46-.39.92 0l6.83 5.72q.46.39-.14.39h-.55q-.6 0-.6.6v5.05q0 .6-.6.6H5.6q-.6 0-.6-.6");
}

.iwpmudbrd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 20.25h.01m3.99 0h.01");
}

.jgj73lbto {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 17h2.25");
}

.m4r17wx7o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 12.5H9.5v2H7.25ZM12 17v-4h2.5v4M3 17h16");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
