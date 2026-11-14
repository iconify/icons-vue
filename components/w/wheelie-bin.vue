<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vm1cy1wkc"/><path class="gmn1oabls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheelie-bin" /></template>
<style>
.gmn1oabls {
  d: path("M7 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm1cy1wkc {
  d: path("M5.5 7.5h13l-1 10.5h-11Zm14 0L5 3.5");
}

</style>
