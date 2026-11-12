<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n06gsnbsc"/><path class="ls_my1bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-vibrate-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ls_my1bjr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3h10v18H7ZM3 6l1 3l-1 3l1 3l-1 3M21 6l-1 3l1 3l-1 3l1 3");
}

.n06gsnbsc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 21V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

</style>
