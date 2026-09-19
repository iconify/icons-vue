<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mo97ssksh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meezanbank" /></template>
<style>
.mo97ssksh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.272 40.536L5.5 36.339l4.925-9.291h5.485l4.925 9.291l-1.772 4.197zm12.499-33.11l-7.576 15.411h6.723l5.28-10.217l5.283 10.217h6.721L28.629 7.426zm9.166 33.148l-1.772-4.197l4.925-9.291h5.485l4.925 9.291l-1.772 4.197z");
}

</style>
