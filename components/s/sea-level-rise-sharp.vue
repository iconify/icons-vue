<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttd9s_b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sea-level-rise-sharp" /></template>
<style>
.ttd9s_b2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75v-9M8.75 6L12 2.75L15.25 6m-12.5 9.75l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2m-18.48 4.5l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2");
}

</style>
