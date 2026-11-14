<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o1b3svmen"/><path class="gd09gc80b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-hand" /></template>
<style>
.gd09gc80b {
  d: path("M2.5 21h11l6.5-4.5a1.75 1.75 0 0 0-2.25-2.75L14.5 16M11.353 4.085l1.294 4.83");
}

.o1b3svmen {
  d: path("m6.523 5.379l9.66-2.588l1.294 4.83l-9.66 2.588ZM2.5 13.5h7a2.25 2.25 0 0 1 0 4.5h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
