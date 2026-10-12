<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0x02ziqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raindrop-off-sharp" /></template>
<style>
.t0x02ziqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 5.86l-3.7 7.05a4.5 4.5 0 1 0 7.96 0l-3.7-7.05L8 5.33zm9.25-2.2l-1.93 3.68a2.5 2.5 0 1 0 4.42 0l-1.93-3.68l-.28-.53zm-.75 10.25l-1.93 3.68a2.5 2.5 0 1 0 4.42 0l-1.93-3.68l-.28-.53z");
}

</style>
