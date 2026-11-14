<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxuapoeep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-rate-compare" /></template>
<style>
.jxuapoeep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 11.5l3.75-3.25L10 11.5V21H2.5ZM14 6l3.75-3.25L21.5 6v15H14Zm-7.75 6h.01m11.49-5.5h.01M4.75 19l3-4m-3 .25h.01m2.99 3.5h.01M16 14.5l3.5-4.5m-3.5.25h.01m3.49 4h.01");
}

</style>
