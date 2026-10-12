<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhwdbjbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shutter-button-sharp" /></template>
<style>
.uhwdbjbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25h14.5v6H4.75zM8 10.75h8v4.5H8zm4-8v5M9.75 5.5L12 7.75l2.25-2.25");
}

</style>
