<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgcu6xbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:superscript-sharp" /></template>
<style>
.dgcu6xbit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 8.75l9 11m0-11l-9 11M16 5.5a1.75 1.75 0 1 1 3.25.9L16 10.5h3.75");
}

</style>
