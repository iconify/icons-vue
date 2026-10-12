<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5xn07bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pebble-sharp" /></template>
<style>
.s5xn07bgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14.13h0l.5-2.13l2.43-.61l.14-.03l2.43-.61l1.5 1.38l1.5 1.37l-.25 1.88l-.25 1.87l-2.49.2l-1.27.1l-2.49.2L3.88 17l-1.13-.75zm11 1.75h0l.25-1.63l1.74-.2l.77-.1l1.74-.2l1.24 1.24l.02.02l1.24 1.24l-.75.75l-.75.75l-1.75-.08l-2.25-.09L14 17.5z");
}

</style>
