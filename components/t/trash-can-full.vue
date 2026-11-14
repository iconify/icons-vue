<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9pfcjabd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trash-can-full" /></template>
<style>
.y9pfcjabd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5L4.75 21h9.5L16 10.5Zm1 0c.5-4 3.5-5 5.5-3.5c1.5-3 5-2 5.5 3.5m4.565-1.669l2.954.521l-2.084 11.817l-2.954-.521Z");
}

</style>
