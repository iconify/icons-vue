<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="os_q9lx8d"/><path class="wv1d60b4r"/><path class="e6a0j5boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:melting-face-sharp" /></template>
<style>
.e6a0j5boj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 13.75l2.054 1.232l2.196-.732l2.1-.7l.65-1.3");
}

.os_q9lx8d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 9.25 0 0 1 18.5 0v2.25l-1.5 2l-.667.889l1.667 1.111c.75.5.5 1.5-1 1.5H15.5v1.5h-2v-1.5h-5v.75H7v-.75H4.25c-1.5 0-1.75-1-1-1.5l1.594-1.062L4.25 16l-1.5-2z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wv1d60b4r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.75h.01m5.99.5h.01");
}

</style>
