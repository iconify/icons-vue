<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7qfvhbds"/><path class="slc-tqbci"/><path class="ed-0uxb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radon-test" /></template>
<style>
.ed-0uxb4i {
  d: path("M12 14.5h.01");
}

.slc-tqbci {
  fill: currentColor;
  d: path("m12.75 16l1.5 2.25a4.25 4.25 0 0 1-4.5 0l1.5-2.25a1.75 1.75 0 0 0 1.5 0Zm0-3l1.5-2.25a4.25 4.25 0 0 1 2 3.75h-2.5a1.75 1.75 0 0 0-1-1.5Zm-2.5 1.5h-2.5a4.25 4.25 0 0 1 2-3.75l1.5 2.25a1.75 1.75 0 0 0-1 1.5Z");
}

.t7qfvhbds {
  d: path("M2.5 11L12 3l9.5 8v10.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
