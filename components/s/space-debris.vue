<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yl6vav4bk"/><path class="jzli4zqdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-debris" /></template>
<style>
.jzli4zqdw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4.5h.01m3.99 2h.01M11.5 21h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yl6vav4bk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.38 7.59l4.49-2.93q.63-.41.94.27l1.63 3.64q.31.68-.33 1.07l-3.72 2.22q-.64.39-1.07-.22L3.18 8.61q-.43-.61.2-1.02m9.51 5.27l4.47-2.72q.64-.39 1.03.25l2.22 3.72q.39.64-.25 1.03l-4.47 2.72q-.64.39-1.03-.25l-2.22-3.72q-.39-.64.25-1.03m2.36-1.11L18 16.5m-13.28.34l2.81-.93q.47-.16.59.33l.76 3.02q.12.49-.35.65l-2.81.93q-.47.16-.59-.33l-.76-3.02q-.12-.49.35-.65");
}

</style>
