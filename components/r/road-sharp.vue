<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhz2rcb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-sharp" /></template>
<style>
.lhz2rcb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h5l.25.97l4.25 16.56l.25.97H4.25l.25-.97L8.75 3.72L9 2.75zm2 2.75v2m0 3.25v2.5m0 3.25V19");
}

</style>
