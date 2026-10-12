<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhrk5lb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wine-sharp" /></template>
<style>
.bhrk5lb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10l.5 4.5a5.5 5.5 0 0 1-11 0Zm-.44 4h10.88m-5.44 6v8.5m-3.75 0h7.5");
}

</style>
