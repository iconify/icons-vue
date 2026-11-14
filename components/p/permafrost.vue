<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-sm4byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:permafrost" /></template>
<style>
.z9-sm4byp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-19 5h2L6 11.75L7.5 9h3l1.5 2.75L13.5 9h3l1.5 2.75L19.5 9h2m-19 7q4.75-2 9.5 0t9.5 0M7 20h.01M12 20h.01M17 20h.01");
}

</style>
