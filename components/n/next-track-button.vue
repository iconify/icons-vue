<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uy_i21k3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:next-track-button" /></template>
<style>
.uy_i21k3w {
  fill: currentColor;
  d: path("M53.213 10.788c-11.715-11.717-30.711-11.717-42.426 0c-11.716 11.715-11.716 30.711 0 42.426s30.711 11.715 42.426 0s11.716-30.711 0-42.426M52 46h-5.219V32l-17.39 14V32L12 46V18l17.392 14V18l17.39 14V18H52z");
}

</style>
