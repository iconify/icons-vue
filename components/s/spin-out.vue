<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfdo_vv-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spin-out" /></template>
<style>
.xfdo_vv-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.52 13.591l7.071-7.071l3.889 3.889l-7.071 7.071Zm4.95-4.95l3.889 3.889m-6.718-1.06l3.889 3.889M4 12a8 8 0 0 1 8-8m-1.75-1.75L12 4l-1.75 1.75M20 12a8 8 0 0 1-8 8m1.75-1.75L12 20l1.75 1.75");
}

</style>
