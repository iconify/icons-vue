<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj43xwb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-signature-sharp" /></template>
<style>
.mj43xwb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 3.75l1.231-1h2.019c1.75 0 3 .75 3 1.9s-1.3 1.85-3 1.85c1.9 0 3.25.75 3.25 1.95c0 1.25-1.35 2.05-3.25 2.05H9.731L8.5 9.5m5.25 11.75V13.5L8 19h8.5");
}

</style>
