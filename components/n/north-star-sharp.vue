<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2h9ytb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:north-star-sharp" /></template>
<style>
.z2h9ytb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.16 3.33l1.68 6.09l.16.58l.56.21l4.13 1.58l.56.21l-.56.21l-4.13 1.58L14 14l-.16.58l-1.68 6.09l-.16.58l-.16-.58l-1.68-6.09L10 14l-.56-.21l-4.13-1.58l-.56-.21l.56-.21l4.13-1.58L10 10l.16-.58l1.68-6.09l.16-.58zM16 8l1.5-1.5M8 8L6.5 6.5M16 16l1.5 1.5M8 16l-1.5 1.5");
}

</style>
