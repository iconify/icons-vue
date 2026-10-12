<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmqmmbsaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:math-sharp" /></template>
<style>
.zmqmmbsaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v13.5H2.75zm3.5 6.75h3.5M8 7.75v3.5m4.75-2.75h5m-5 2.25h5M12 16.25v5m-3.5 0h7");
}

</style>
