<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfp0jabcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:send-x-sharp" /></template>
<style>
.tfp0jabcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.82 3.61L4.18 9.64l-.93.36l.92.4l5.66 2.45l.92.4l.4.92l2.45 5.66l.4.92l.36-.93l6.03-15.64l.36-.93zm-9.07 9.64L15 9");
}

</style>
