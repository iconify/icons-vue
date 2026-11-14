<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="imi1lwbqa"/><path class="nqchmx61f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-closing-balance" /></template>
<style>
.imi1lwbqa {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8M8 10h8");
}

.nqchmx61f {
  d: path("M7 13.5h10V18H7Zm2.25 2.25h5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
