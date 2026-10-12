<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0e7xo-qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:midi-keyboard-sharp" /></template>
<style>
.f0e7xo-qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.25h18.5v10H2.75zm4.65 3.5v6.5m4.6-6.5v6.5m4.6-6.5v6.5m-4.6-10V5h5.5m0-1.75h3.75v3.5H17.5z");
}

</style>
