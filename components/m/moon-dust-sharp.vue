<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v9gg59bde"/><path class="gttf8eb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-dust-sharp" /></template>
<style>
.gttf8eb9g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 13.75h.01M9.5 21h.01M17 21h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v9gg59bde {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3a4 4 0 0 0 5.25 5.25A5.5 5.5 0 1 1 12.5 3ZM3.75 17.25l2.06-1.5l2.07 1.5l2.07 1.5l2.05-1.5l2.05-1.5l2.08 1.5l2.08 1.5l2.04-1.5");
}

</style>
