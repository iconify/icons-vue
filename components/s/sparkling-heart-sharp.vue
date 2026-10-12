<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5r8scc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkling-heart-sharp" /></template>
<style>
.n5r8scc8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 20.79h-.467l-.363-.3c-2.47-2.06-5.73-4.69-5.73-8.21c0-2.03 1.53-3.68 3.49-3.68h1.781l1.289 1.65l1.289-1.65h1.791c1.95 0 3.49 1.65 3.49 3.68c0 3.53-3.26 6.15-5.74 8.21l-.347.3zm7.5-18.04l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42L15 5.5l2.42-.33z");
}

</style>
