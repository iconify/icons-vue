<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zs2n7embr"/><path class="lfxu3cb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-bereavement" /></template>
<style>
.lfxu3cb3i {
  d: path("M12 2.5c4 0 4.75 4.75 2.25 7.75l-8 10.25l-2-.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs2n7embr {
  d: path("M12 2.5c-4 0-4.75 4.75-2.25 7.75l8 10.25l2-.75");
}

</style>
