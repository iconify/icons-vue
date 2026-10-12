<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ilkz7hbdj"/><path class="ljucq2cls"/><path class="z4t0o-brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pos-terminal-sharp" /></template>
<style>
.ilkz7hbdj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.25h14.5v14H4.75z");
}

.ljucq2cls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 10V2.75h8.5V10Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z4t0o-brg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 14.5h.01m3.24 0h.01m3.24 0h.01m-6.51 3.25h.01m3.24 0h.01m3.24 0h.01");
}

</style>
