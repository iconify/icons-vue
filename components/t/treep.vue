<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2i8ngakm"/><circle class="xlvr0_jyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:treep" /></template>
<style>
.m2i8ngakm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.34 43.5c-.432-12.378 2.222-25.563 10.745-25.39c5.25.107 7.862 5.92 6.087 10.314c-1.377 3.375-9.349 8.89-15.52.74c-2.453-3.238-8.385-10.942 5.496-20.228m-5.151-.706l5.151.705m0 .001l-.705 5.151");
}

.xlvr0_jyn {
  cx: 30.714px;
  cy: 6.457px;
  r: 1.958px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
