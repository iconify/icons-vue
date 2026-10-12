<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3mhr80cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volume-boost-sharp" /></template>
<style>
.w3mhr80cr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.5V8h3.7l4.4-3.7l1.569-1.406L13.35 5v14l.069 2.106L11.85 19.7L7.45 16h-3.7v-1.5Zm14.5 7.25v-9.5m-3 3l3-3l3 3");
}

</style>
