<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fjmk1tc6j"/><path class="xt91z5b1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:refund" /></template>
<style>
.fjmk1tc6j {
  d: path("M12 4a8 8 0 1 1-8 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xt91z5b1e {
  d: path("m14 2l-2 2l2 2m.25 3.75C14 9 13.2 8.5 12 8.5c-1.25 0-2.25.6-2.25 1.5c0 2 4.5 1.5 4.5 3.75c0 1.05-1 1.75-2.25 1.75s-2.1-.5-2.25-1.25M12 7v1.5m0 7V17");
}

</style>
