<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1pdylboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nmr-spectrum" /></template>
<style>
.h1pdylboo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5h3l1-9.5l1 9.5h3l1-14l1 14H15l1-5.5l1 5.5h1.5l.75-3.5l.75 3.5h1.5M2.5 21h19");
}

</style>
