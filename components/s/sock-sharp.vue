<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dao2-jmux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sock-sharp" /></template>
<style>
.dao2-jmux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75h6.5V12l4.65 4.3a2.75 2.75 0 0 1-1.87 4.95H8v-3.5Zm0 3.5h6.5m2 11l-1.75 2.5");
}

</style>
