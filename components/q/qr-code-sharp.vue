<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g8rxpikcz"/><path class="s1c60_bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:qr-code-sharp" /></template>
<style>
.g8rxpikcz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h7v7h-7zm10.5 0h7v7h-7zm-10.5 10.5h7v7h-7z");
}

.s1c60_bus {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01m10.49 0h.01M6.75 17.25h.01m7.74-2.75h.01m5.49 0h.01m-2.76 2.75h.01M14.5 20h.01M20 20h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
