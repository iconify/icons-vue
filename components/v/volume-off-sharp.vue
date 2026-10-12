<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wewtvwb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volume-off-sharp" /></template>
<style>
.wewtvwb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.5V8h3.7l4.4-3.7l1.569-1.406L13.35 5v14l.069 2.106L11.85 19.7L7.45 16h-3.7v-1.5Zm12.5 0l4.5 4.5m0-4.5l-4.5 4.5");
}

</style>
